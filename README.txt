KURT DHYLAN MOTO SHOP INVENTORY V3 - GITHUB UPLOAD PACKAGE

1. Extract this package.
2. Upload ALL extracted contents to the ROOT of the GitHub repository:
   KurtDhylanMotoShopInventoryV3

Expected repository layout:

.github/workflows/build-android.yml
KurtDhylanMotoShopInventoryV3_Source.zip
README.txt

3. Open GitHub Actions.
4. Select "Build Kurt Dhylan Moto Shop Inventory V3 APK".
5. Press "Run workflow".

The workflow:
- finds KurtDhylanMotoShopInventoryV3_Source.zip
- extracts it
- finds the MAUI .csproj specifically (not the .sln)
- installs the MAUI Android workload
- restores the .csproj
- publishes an Android APK
- uploads the APK as a GitHub Actions artifact

IMPORTANT:
Do not upload this outer package ZIP as a single file. Extract it first, then upload the files/folders shown above.
