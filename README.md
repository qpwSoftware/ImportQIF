# ImportQIF
Use ImportQIF to convert CSV/Excel/OFX/QFX/QIF file to QIF/QFX format that Quicken allows.

This program is only compiled for Windows.

If you are using Microsoft Money use the Option "Remove QIF Account Information".
For Quicken Windows US and Canadian the QIF format uses the US date format, only change the "Converted.QIF date format" if you are using a program that is using a different QIF import format.

The most basic purpose of ImportQIF is to add the account name and type to a QIF file to bypass the restriction in Quicken Windows US that only allows importing into asset and liability accounts (Quicken Subscription removed this restriction, but took away a lot of functionality like using memorized payees).

Warning!! Quicken Subscription breaks a lot of the QIF transaction import functionality.  There are workarounds in ImportQIF except for matching existing transactions, that is something ImportQIF can't do anything about.

It also has options for translating dates, and decimal separator, and swapping the payee and memo fields. The default is to register ImportQIF as the default QIF file handler, so that when you open a QIF from your web browser or File Explorer, ImportQIF will be run, and you can select one button to save the converted QIF to your desktop.   It is supported to translate non-US dates in QIF files to US dates.
Also ImportQIF adds the feature of automatically importing the converted QIF file into Quicken and also to convert from OFX (MS Money), QFX, CSV, Excel files into QIF files.  Please note that at present conversions from OFX/QFX are not supported for loan/liability accounts.

Limited support for importing investment transactions through OFX/QFX/CSV/Excel format(Excel file imports require Excel to be installed on the machine).

Ability to convert from a CSV or Excel file to a QFX file instead of a QIF file.  Note to use a QFX file your version of Quicken has to be supported by Quicken Inc.  What's more there are several restrictions that the QFX mode imposes.  The QFX format doesn't support categories or split transactions.  And the US version of Quicken will only allow importing for the USD currency.  The Canadian version can import in different currencies like CAD and USD.

But using the QFX format will allow for matching of transactions and using Quicken's system for filling in the categories even in the latest versions of Quicken which have dropped these features for QIF file imports.

To Install ImportQIF.
Download ImportQIF.zip, and extract that ZIP file to any folder you like.

To run ImportQIF just double click on ImportQIF.exe or a shortcut to it.
​
To create a shortcut to ImportQIF.exe right click on it and drag to wherever you want the shortcut and select "Create shortcut here".

To remove ImportQIF just delete this folder.

To remove the user settings for ImportQIF click on the Windows Start button and type in %APPDATA% and then enter.
Delete the QuicknPerlWiz folder.

Note there is various ways to open the file you want converted.  There is File -> Open..., but you can also use Windows' Open With menu selection to open the file with ImportQIF and even make it the default program to use when you open the file in File Explorer or your web browser.  To invoke the Open With menu right click on the file.

For documentation press F1 on each screen, or you can read the PDF files in the ImportQIF folder.
