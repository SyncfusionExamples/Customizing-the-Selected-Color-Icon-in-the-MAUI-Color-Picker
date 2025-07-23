# Customizing-the-Selected-Color-Icon-in-the-MAUI-Color-Picker

This article illustrates how to customize the selected color icon in the MAUI Color Picker control.

## Sample

```xaml
    <inputs:SfColorPicker x:Name="colorPicker">
        <inputs:SfColorPicker.SelectedColorIcon>
            <FontImageSource FontFamily="MauiMaterialAssets" Glyph="&#xe749;" Color="{Binding Source={x:Reference colorPicker},Path=SelectedColor}"/>
        </inputs:SfColorPicker.SelectedColorIcon>
    </inputs:SfColorPicker>
```

## Requirements to run the demo

To run the demo, refer to [System Requirements for .NET MAUI](https://help.syncfusion.com/maui/system-requirements)

## Troubleshooting:
### Path too long exception

If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise from using or viewing the samples. The samples are for demonstrative purposes. If you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion's samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion's samples
