# KUtils
> Kakaotalk bot Utils

<img src="https://raw.githubusercontent.com/sungbin5304/KUtils/master/logo.gif" width="50%" height="50%">

-------

## What is KUtils?
> KUtils is a library designed to make it easy for users to create Kakaotalk Bot.

## How can I use KUtils?
> Add the KUtils source code to the top of your script.

## All Methods.
**KUtils.**
- setPathString(String path)
- ~~makeVibration(int time)~~ (Not yet made)
- makeNotification(String title, String content)
- makeToast(String content)
- ~~makeDialog(String title, String content)~~ (Not yet made)
- makeRandom(int min, int max)
- save(String fileName, String fileContent)
- delete(String fileName)
- makeFile(String fileName)
- makeFolder(String folderName)
- toBoolean(String true/false)
- toNumber(String number)
- toString(Object obj)
- copy(String content)
- error(Exception e)
- getHtml(String adress)
- deleteHtml(String htmlCode)

**String.prototype.**
- replaceAll(String ori, String pre)
- replaceFirst(String ori, String pre)
- replaceLast(String ori, String pre)
- ~~replaceCenter(String ori, String pre)~~ (Not yet made)
- contains(String content)
- trimAllLine()

**Array.prototype.**
- contains(String content)
- ~~replaceArrayData(String ori, Content pre)~~ (Not yet made)
- ~~deleteArrayData(String content)~~ (Not yet made)

~~**RegReplace.**~~ (Not yet made.)
- deleteAllKor()
- deleteAllNumber()
- deleteAllSC()
- deleteAllNotKor()
- deleteAllNotNumber()
- deleteAllNotSC()
> SC : Special Characters

## Warning!
KUtils only works on [MessengerBot](https://play.google.com/store/apps/details?id=com.xfl.kakaotalkbot).
