
# Изменение миров.
Switch worlds from editor mode to Minecraft preview and and vice versa without export-import.

# Intro.
According to Microsoft's instructions  https://learn.microsoft.com/en-us/minecraft/creator/documents/editoroverview#editor-file-operations---create-import-export, to switch the world from editor mode to Minecraft preview and vice versa, you must follow this ##### instruction. But I will show you a more correct way, which I came up with on 03/09/2023, the day after the release of Minecraft preview 1.19.80.02

But why did I call this instruction from Microsoft - #######? it's simple, because imagine that you have created a 5 GB world in Minecraft preview or editor mode and you need to send it to Minecraft preview or editor mode. you will first have to export this world as an archive using game functions, then import it using game functions, and this process, given the size of your world, will take quite a bit of time. It is an absolutely stupid decision on the part of Mojang not to provide for this. in fact, only one NBT tag in the level.dat - (isEditorWorld: 1) file is responsible for the fact that the world will be displayed in the list of worlds editor mode or Minecraft preview its presence or absence will affect whether the world will be in the list of some of the games or not.
and it will only take you a few seconds to edit this NBT tag, which is much more reasonable, so use my instruction, not nonsense from Microsoft!

# Guide.

First download (UME) Universal Minecraft Editor from web.archive because Matt G blocked the download from his site: https://web.archive.org/web/20211024121354/https://www.universalminecrafteditor.com/software/UniversalMC_setup.exe?fdl=1
you will need exactly UME because NBT studio and NBT Explorer for some reason believe that the level.dat file from new worlds is empty.

now assuming that you have already created a world in Minecraft Preview and want to send it to Editor mode. You need to open UME and press one of these buttons: ![IMG_20230309_131645](https://user-images.githubusercontent.com/81485476/223963037-8b9ca96b-cb25-4db2-b25b-f1bc97367029.jpg)

then in the window that opens, click this button:

![IMG_20230309_131955](https://user-images.githubusercontent.com/81485476/223962249-19d15a12-77a1-49cf-8182-ec321ebbd9d4.jpg)

