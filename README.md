# AndroidGradleLibFlavorResIssue

To reproduce:
run `./gradlew clean assemblePpeDebug assembleDevDebug`

Then inspect the dev APK and notice that the value of `aaa_lib_test_gradle` is *ppe*, not *dev*
