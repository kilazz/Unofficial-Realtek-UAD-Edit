## Realtek UAD Edit Generic/OEM
#### Compatibility >
- Windows 10 x64 19041+
#### Removal >
- Uninstall Realtek Audio Driver and all packages, check via [Rapr][DriverStoreExplorer]
- Restart PC
#### Installation Generic >
- Unzip the .7z(Zstandard) archive
- Run _CertTest/`CertTest.bat`
- Installation using Driver/`Setup.exe` or `Install.bat`
- Restart PC
#### Installation OEM >
- Unzip the .7z(Zstandard) archive
- Delete Driver\UAD64\Realtek\ExtRtk_9718.1\ `HDXRTKExt_RTK_PC.inf`
- Place only one HDXRTKExt_ and folder OEM
- Open Driver\UAD64\Realtek\ `ExtRtk_9718.1.7z` and place `HDXRTKExt_DOLBY_PC.inf`/`HDXRTKExt_XPERI4_PC.inf`/`HDXRTKExt_AVO_PC.inf` in Driver\UAD64\Realtek\ExtRtk_9718.1\
- Open Driver\UAD64\Realtek\ `ThirdParty.7z` and place `Dolby/DTS/Nahimic` in Driver\UAD64\Realtek\ThirdParty\
- Run _CertTest/`CertTest.bat`
- Installation using Driver/`Setup.exe` or `Install.bat`
- Restart PC

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
