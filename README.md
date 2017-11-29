# ScannerView
Custom Android View for Scanning QR Codes like for WhatsApp Web

<img src="https://media.giphy.com/media/3o6fJ3jykjcDnWYFIk/giphy.gif"/>

## Usage

1. Copy `ScannerView.java` into your project.
2. Extend `res/values/attrs.xml` with the `declare-styleable` element in `attrs.xml`. If you don't have an `res/values/attrs.xml` you can directly use the whole `attrs.xml`.
3. Use the `ScannerView` your layout XML file:
   ```
   <com.yourname.package.ScannerView
       android:layout_width="match_parent"
       android:layout_height="match_parent"/>
    ```
    
## Customization
To specify the custom attributes, add `xmlns:custom="http://schemas.android.com/apk/res-auto"` to your root layout element. Then you can set `custom:movingLineColor="@color/colorPrimary"` in the `ScannerView` element, for example.

You can customize a lot, as you can see in `attrs.xml`:

```
<attr name="frameWidthPercentage" format="float" />
<attr name="frameHeightPercentage" format="float" />
<attr name="frameAspectRatio" format="float" />
<attr name="movingLineWidth" format="dimension" />
<attr name="frameLineWidth" format="dimension" />
<attr name="orthogonalFrameLineLength" format="dimension" />
<attr name="paddingColor" format="color" />
<attr name="movingLineColor" format="color" />
<attr name="frameColor" format="color" />
<attr name="upAndDownSeconds" format="float" />
```
