# AAPS Objectives Quiz Answers (Objective 2)

All answers are sourced from the constraints plugin (`plugins/constraints/src/main/kotlin/.../objectives/objectives/Objective2.kt` and the associated string resources).

✅ = Correct answer &nbsp;&nbsp; ❌ = Incorrect answer

---

## Q1 — Prerequisites: "What is essential to set up and use AAPS?"

- ✅ Nightscout, to keep a log of all data and review settings.
- ✅ A way to build AAPS. Either via a browser or a computer with Android Studio installed.
- ✅ A compatible insulin pump if you are planning to run a closed loop.
- ❌ Experience in programming or editing code.

---

## Q2 — Prerequisites (2): "What is essential to set up and use AAPS?"

- ✅ Validated information to set up a profile (ISF, I:C ratio, basal rates, DIA etc.).
- ✅ A compatible Android device (e.g. mobile/cell phone, full Android watch, or tablet).
- ❌ AAPS requires an internet connection to run in the closed loop.
- ✅ A supported CGM and appropriate app to receive blood glucose values on the phone/device.

---

## Q3 — Basal, ISF, and I:C Testing: "When should these values be validated?"

- ❌ Once set and validated, these values should not change over time.
- ✅ When experiencing frequent high or low blood glucose.
- ❌ At least once per week.
- ✅ Before starting looping.

---

## Q4 — Duration of Insulin Action (DIA): "What is true about DIA?"

- ✅ You should set the value for DIA in your profile.
- ✅ The minimum allowed value is 5 hours.
- ❌ If you are satisfied that the value for DIA that you used in your pump before AAPS worked well, there is no need to change this when you start looping.
- ✅ You should determine for yourself the appropriate value for DIA.

---

## Q5 — Insulin Sensitivity Factor (ISF)

- ✅ Reducing ISF values will lead to more insulin delivery to correct for an above target blood glucose.
- ❌ ISF should be entered in your AAPS Preferences.
- ❌ Raising ISF values will lead to more insulin delivery to cover a specific amount of carbs.
- ❌ Raising or lowering ISF does not affect insulin delivery when blood glucose levels are below target.

---

## Q6 — Insulin to Carbohydrate Ratio (I:C ratio)

- ✅ Higher I:C ratios lead to less insulin delivered for a given amount of carbs.
- ❌ Lower I:C ratios lead to less insulin delivered for a given amount of carbs.
- ✅ You can use more than one value for I:C ratio in your profile.
- ❌ If you change your ISF in your profile you should always change your I:C ratio too.

---

## Q7 — Hypo Temp-Target: "What is the primary reason to set a hypo temp target?"

- ✅ To prevent AAPS from overcorrecting for a blood glucose rise caused by the fast-acting carbs used to treat a hypo.
- ❌ To correct for a hypo induced as a result of exercise.
- ❌ To correct for hypos caused by incorrect basal rate settings.
- ❌ To prevent blood glucose from going low if there is already a 0% temporary basal rate running.

---

## Q8 — Profile Switching: "When specifying a 90% profile switch, which answers are true?"

- ✅ Basal rates will be 10% lower.
- ✅ ISF will be 10% higher.
- ❌ The value of the I:C ratio will be a 10% lower number.
- ❌ ISF and I:C ratios will be unchanged.

---

## Q9 — Profile Switching: "When specifying a 120% profile switch, which answers are true?"

- ❌ Target blood glucose will be 20% higher.
- ✅ Basal rates will be 20% higher.
- ✅ Target blood glucose will be unchanged.
- ❌ ISF will be 20% higher.

---

## Q10 — Profile Switching: "If you get up 2 hours earlier than usual, how should you notify AAPS of the change in your schedule?"

- ❌ Initiate a profile switch with a timeshift of 2.
- ✅ Initiate a profile switch with a timeshift of -2.
- ❌ Set eating soon temporary target.
- ❌ Do a profile switch to more than 100%.

---

## Q11 — Changes to profiles

- ✅ Basal rates, ISF, I:C ratios, etc., should be set in profiles.
- ✅ Activating changes to your Nightscout Profile requires your AAPS phone to have an internet connection.
- ❌ Editing profiles to change values is sufficient to enact any changes made.
- ✅ Multiple profiles can be set up and selected to accommodate changing circumstances (e.g., hormonal changes, shift working, weekdays/weekend lifestyle).

---

## Q12 — Exercise and Profiles: "How can you use profiles to best help the system deal with aerobic exercise?"

- ❌ Do a profile switch to more than 100%.
- ✅ Do a profile switch to less than 100%.
- ❌ Suspend the loop.
- ❌ Leave the profile set to 100%.

---

## Q13 — Exercise and Temporary Targets: "How can you use temporary targets to best help the system deal with aerobic exercise?"

- ✅ Set an activity blood glucose target starting a suitable time before beginning exercise.
- ❌ Set an activity blood glucose target after finishing exercise.
- ❌ Leave your blood glucose target unchanged.
- ❌ Wait until blood glucose drops below your hypo temp target and then eat 15 g of fast acting carbohydrates.

---

## Q14 — Noisy CGM Readings: "What should be done if CGM data is noisy?"

- ❌ Do nothing - AAPS will deal with it.
- ✅ Disable the closed loop to avoid possible over or underdosing.
- ✅ Replace consistently noisy or inaccurate sensors.
- ✅ Verify that your CGM app provides smoothed data.

---

## Q15 — Reasons for applying "Disconnect pump" in AAPS

- ❌ This is unnecessary as insulin will not be delivered if the pump is physically disconnected.
- ✅ It prevents AAPS from accounting for insulin that was not delivered whilst the pump is physically disconnected.
- ❌ It will not stop insulin delivery if the pump remains connected to your body.
- ❌ It will send AAPS into open loop mode.

---

## Q16 — Insulin Plugins: "Which insulin should you use with the Ultra-Rapid Oref plugin?"

- ❌ NovoRapid®/Novolog®
- ❌ Humalog®
- ❌ Actrapid®/Humulin R®/"regular" human insulin.
- ✅ Fiasp®

---

## Q17 — Sensitivity Plugins

- ✅ Sensitivity plugins allow AAPS to adjust for temporary or short-lived changes in insulin sensitivity (for example hormonal changes or issues with absorption at the infusion site).
- ❌ Sensitivity plugins provide the user with suggested changes to basal rates, I:C ratios, and ISF that can be used to edit profile.
- ✅ Logging a cannula change will reset the Autosens ratio back to 100%.
- ✅ Some of the plugin options have configurable time ranges and the user can set them.

---

## Q18 — AAPS Settings: "What are the best practices for backing up your settings?" (Part 1)

- ❌ You do not need to export your settings provided that you make a note of them.
- ✅ Export your settings after you finish completing an objective.
- ✅ Export your settings after changing any of your settings.
- ✅ Export your settings after you finish your initial set-up and have set your Preferences.

---

## Q19 — AAPS Settings: "What are the best practices for backing up your settings?" (Part 2)

- ✅ Export your settings locally using the maintenance menu.
- ✅ Your settings file is found in the folder Internal Storage/AAPS/preferences on your phone.
- ✅ Copy your preferences file to a safe location outside of your phone (e.g. by using a cloud drive, connecting a cable to a computer, email, etc.)
- ❌ If your phone is damaged or lost, there are easy ways to remotely recover your settings without a backup.

---

## Q20 — Updating AAPS

- ✅ You need to have Git installed and configured on your computer.
- ❌ If you have difficulty building the apk, you can install an apk that has been built by a friend.
- ✅ You should save and note the location of your keystore and use the same signing key for updates as for your previous installation.
- ✅ When updated versions of AAPS are released, the earlier versions may be remotely limited after a specified time.

---

## Q21 — Troubleshooting: "Where can you look for help with AAPS?"

- ✅ You can ask for advice in the AAPS Users Facebook group.
- ✅ You should read (and re-read) the AAPS documentation.
- ✅ You can ask for advice, discuss technical problems and feature requests in the AAPS Discord.
- ✅ You can submit issues such as bugs and feature requests at Github.
- ❌ You should ask your diabetes clinic/endocrinologist.

---

## Q22 — Carb Entry Errors: "What should you do if you've made an incorrect carb entry?"

- ❌ Bolus with insulin using the infusion set prime menu.
- ✅ Delete the incorrect entry in Treatments and enter the correct new carb value.
- ❌ Do nothing – AAPS will make the appropriate adjustments.
- ❌ Bolus with insulin using the Insulin (bolus) button in Overview.

---

## Q23 — Insulin delivery/entry errors: "What should you do if you received less insulin than the pump history suggests e.g. due to an occlusion, a failed cannula or forgetting to reattach the pump after a shower?"

- ❌ Delete insulin data from Nightscout Careportal to remove it from the pump history.
- ✅ Compare values in AAPS and pump history (if pump supports this).
- ✅ Bolus a proportion of your calculated 'missed' insulin by either syringe/pen or using a prime.
- ❌ Do nothing – AAPS will make the appropriate adjustments.

---

## Q24 — Insulin on Board (IOB)

- ✅ IOB value is affected by issued temporary basals.
- ❌ High temp basal will not be given when your blood sugar is below target.
- ✅ Negative IOB for a substantial period in the absence of exercise suggests your profile is too strong and less insulin is needed in your settings.
- ✅ Positive IOB for a substantial period suggests insulin resistance or unannounced meals.

---

## Q25 — Carbs on Board (COB): "How does changing ISF affect COB calculation?"

- ✅ Increasing ISF will make the calculated carb absorption time longer.
- ❌ Increasing ISF will make the calculated carb absorption time shorter.
- ❌ Increasing ISF will not affect calculated carbs absorption.

---

## Q26 — Carbs on Board (COB): "How does changing IC affect COB calculation?"

- ❌ Increasing IC will make the calculated carb absorption time longer.
- ✅ Increasing IC will make the calculated carb absorption time shorter.
- ❌ Increasing IC will not affect calculated carbs absorption.

---

## Q27 — Carbs on Board (COB): "How does changing profile percentage affect COB calculation?"

- ❌ Setting profile to 150% will make the calculated carb absorption time longer.
- ❌ Setting profile to 150% will make the calculated carb absorption time shorter.
- ✅ Setting profile to 150% will not affect calculated carbs absorption.

---

## Q28 — Carb entry and boluses

- ✅ Only grams should be used for estimating and recording carbohydrates consumed.
- ❌ Carbohydrates consumed can be recorded using an appropriate exchange system (e.g. DAFNE "CHO" exchanges or European "Bread Units").
- ✅ AAPS uses a dynamic model to estimate carb absorption and calculate COB.
- ✅ If blood glucose levels are outside acceptable values (too low or too high) the bolus calculator can be used to provide suggestions for carb or insulin corrections.

---

## Q29 — e-carbs: "What could you use e-carbs (extended carbs) for?"

- ✅ To schedule carbs in the future, possibly distributed over an interval (similar to an extended bolus distributing insulin over an interval).
- ❌ For logging 'free' exercise carbs you want to hide from AAPS.
- ✅ e-carbs (distributed in the future) can assist AAPS in dealing with high fat/protein meals.
- ❌ For logging rescue carbs you use to treat low blood glucose.

---

## Q30 — Remote Monitoring: "How can you monitor AAPS remotely?"

- ✅ AAPSClient app, Nightscout app and Nightscout webpage all allow you to follow AAPS remotely.
- ✅ Other apps (e.g. Dexcom follow, xDrip running in follow mode) allow you to follow some parameters remotely, but use different algorithms so may have inaccurate IOB or COB values.
- ✅ To follow AAPS remotely, both devices must have internet access (e.g. via Wi-Fi or mobile/cellular network data).
- ❌ AAPSClient used as a remote follower will both monitor and provide full control of AAPS.

---

## Q31 — Other Medication (Declaration)

> AAPS reduces basal rates or suspends insulin delivery to raise blood sugar. Drugs in the class SGLT2 inhibitors (gliflozins) can prevent increases in blood glucose and, thus, can produce a dangerous insulin deficiency leading to DKA.
> Common brand names are: Invokana®, Forxiga®, Jardiance®, Steglatro®, Suglat®, Apleway®, Deberza®, Synjardy®, Vokanamet®, Xigduo®.
> I hereby promise that I will not take such drugs when using AAPS or will deactivate the loop before using such drugs.

- ✅ Yes (accept declaration)
- ❌ No
