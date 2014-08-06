# Install Source Tree


1. Browse to [Source Tree Home Page](www.sourcetreeapp.com).
2. Download and run the installer.
3. Launch SourceTree. It will prompt you for some configuration information.
4. Select: I don't want to use Mercurial.
![SourceTree_Install_1](../images/SourceTree-setup-1.png)
5. Fill in your user information.
![SourceTree_Install_2](../images/SourceTree-setup-2.jpg)
6. We will not generally be using SSH to connect to our Git servers, so accepting the default on this screen if fine.
![SourceTree_Install_3](../images/SourceTree-setup-3.png)
7. You do not need to configure an SSH key. Select No.
![SourceTree_Install_4](../images/SourceTree-setup-4.png)
8. Fill in the host information for the Remote project hosts you have.
![SourceTree_Install_5](../images/SourceTree-setup-5.jpg)
9. At this point the main SourceTree interface will open.
10. Open the options dialog by selecting the Tools → Options menu.
11. Uncheck the option to automatically start the SSH agent.
![SourceTree_Install6](../images/SourceTree-setup-6.jpg)

12. Fill in the Project folder with a convenient location, we recommend `C:\Code\git` (Note that this slightly different than the picture above). This path is the default location to put new Git repositories, you will have a chance to override it when creating or cloning individual repositories later.
13. Click to the "Diff" tab in the Options Menu.
14. Change your **External Diff Tool** and/or **Merge** to P4Merge or KDiff depending on personal preference.
![SourceTree_Install_7](../images/SourceTree-setup-7.png)

15. Change to the **Git** Tab in Options.
16. Verify that the **Global Ignore List** is **empty**.
![SourceTree_Install8](../images/SourceTree-setup-8.png)
17. Click OK.
