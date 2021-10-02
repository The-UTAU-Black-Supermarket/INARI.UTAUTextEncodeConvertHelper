# UTAU TextEncode Convert Helper
Convert voicebanks and USTs from GB2312 (Chinese encoding) to Shift-JIS (Japanese encoding)

## Convert voicebank files
Double click `UTAUTextEncodeConvertHelper.exe` to start the application. Switch to the "File names" tab, then click "Open folder" to select the folder containing files you want to convert. The original file names will appear on the left, and converted file names will appear on the right. Check each conversion option until the result looks correct, then press "Convert" to finish renaming all of the files.

## Convert USTs
You can run the tool standalone or as an UTAU plugin.

When using it standalone, press "Open..." to select the UST file. The original contents will appear on the left and the converted contents will appear on the right. Check each conversion option until the lyrics look correct. Press "Save" to overwrite the current file or "Save As..." to save a separate file.

When using it as an UTAU plugin, it will edit the entire UST that is currently open. Check each option until the lyrics look correct, then press OK to confirm. You cannot convert voicebank filenames in plugin mode.