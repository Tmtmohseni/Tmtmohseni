# Error For Running DameWare.Mini.Remote.Control


Sometimes when you decide to open an app or file or install or open a program on your Windows 10 PC, you might get the error "An administrator has blocked you from running this app".

![6](https://github.com/Tmtmohseni/Error/assets/162871906/2c05f325-04fa-4781-8d46-8c9f0882cb8b)

You get this error because Windows is optimized for protection against malware through Windows Defender and User Account Control (UAC).

You have to Make Changes to the Group Policy by following this stpes 


Step 1: Press WIN + R on your keyboard to open the Run dialogue.

Step 2: In the run dialogue, type in "gpedit.msc" and hit ENTER on your keyboard.

![1](https://github.com/Tmtmohseni/Error/assets/162871906/499609df-50b9-4aad-940e-2b801facd8d6)

Step 3: Under Computer Configuration, expand Windows Settings, Security Settings, and Local Policies.

Step 4: Click on Security Options. Don’t attempt to expand it, just click on it.

![2](https://github.com/Tmtmohseni/Error/assets/162871906/0ba96131-6c9d-46a8-a4d5-59c75f266ffa)

Step 5: Navigate to the bottom and double-click "User Account Control: Run all administrators in Admin Approval Mode".

![3](https://github.com/Tmtmohseni/Error/assets/162871906/bb205b89-511f-4024-b5e4-b866a0faa8a1)

Step 6: Select Disable, click Apply, and then Ok.

![4](https://github.com/Tmtmohseni/Error/assets/162871906/d4668cc6-e348-4cfc-a0ef-b17b2628f4f5)

And At the end, Turn off the Smart App Control

![5](https://github.com/Tmtmohseni/Error/assets/162871906/c1fcb77c-ba20-47f3-8423-c0d007de58ca)
