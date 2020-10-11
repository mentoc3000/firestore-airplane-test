# firestore-airplane-test
Test issues with losing connectivity and accessing firestore cache.

Steps to reproduce:

1. Run the app
2. Go into airplane mode
3. Tap the FAB
4. Observe: app hangs at [line 50](https://github.com/mentoc3000/firestore-airplane-test/blob/5a6c68ddec9eaa7b45a7ba727ea7ac77869d627b/lib/main.dart#L50).
