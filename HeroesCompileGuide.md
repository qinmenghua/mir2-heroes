# What you'll Need #

**An account on**<a href='http://www.lomcn.co.uk/forum/'>LOMCN</a>

- <a href='http://www.lomcn.co.uk/forum/showthread.php?68947-Delphi-7-Enterprise-Download'>Delphi 7 Enterprise</a>

- <a href='http://tortoisesvn.tigris.org/'>TortoiseSVN</a>

- Windows XP is advisable. Issues with components may occur with Vista and 7. VirtualPC will work fine with Delphi.

# Installation #

Install Delphi 7, TortoiseSVN and DBCommander by following there Setup programs. Once everything is installed correctly you will need to pull the latest code from our SVN.

To do this open any folder (Root of your C Drive is preferred but not necessary) and right click any white space. In the context menu select SVN Checkout. Enter the following URL: http://mir2-heroes.googlecode.com/svn/trunk/ and ensure Head Revision is selected.

Press OK and wait for everything to download. (First time could take a while). When everything is done find the Components folder and extract the Components.zip contents to the Components folder.

Install as many of these Components as possible. If errors occur ignore and move on. Some components that should install correctly are **Raize 4.1** (Using the Setup file), **jcl\_jvcl\_20070824** (Install dejoy\_jcl-2007-08-24\_v2.14 first then dejoy\_jvcl-2007-08-24\_v3.33, **DirectX** and **indy10.0.52\_d7**. Visit LOMCN for more help on compiling these components.

To check if everything was successful open M2Engine\M2Server.dpr and Build the project. If no errors occurred you should have a new compiled M2Server.exe in MirServer\Mir200. Do the same with MirClient and the other project files.