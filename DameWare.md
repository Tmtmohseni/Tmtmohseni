# Error For Running DameWare.Mini.Remote.Control

Sometimes when you decide to open an app or file or install or open a program on your Windows, you might get the error "An administrator has blocked you from running this app".

![6](https://github.com/Tmtmohseni/Tmtmohseni/assets/162871906/888a0281-00e5-45a1-bed0-b248aca39dc4)


You get this error because Windows is optimized for protection against malware through Windows Defender and User Account Control (UAC).

You have to Make Changes to the Group Policy by following this stpes 


Step 1: Press WIN + R on your keyboard to open the Run dialogue.

Step 2: In the run dialogue, type in "gpedit.msc" and hit ENTER on your keyboard.

![1](https://github.com/Tmtmohseni/Tmtmohseni/assets/162871906/e93f6d9a-0cc0-4749-b6fc-812056ae5da0)


Step 3: Under Computer Configuration, expand Windows Settings, Security Settings, and Local Policies.

Step 4: Click on Security Options. Don’t attempt to expand it, just click on it.

![2](https://github.com/Tmtmohseni/Tmtmohseni/assets/162871906/288918fd-a20f-452b-83a3-0fe9a14da7e2)


Step 5: Navigate to the bottom and double-click "User Account Control: Run all administrators in Admin Approval Mode".

![3](https://github.com/Tmtmohseni/Tmtmohseni/assets/162871906/2c97fb20-44ae-4446-ad9a-37e0462495e6)


Step 6: Select Disable, click Apply, and then Ok.

![4](https://github.com/Tmtmohseni/Tmtmohseni/assets/162871906/050adfb7-42b9-4cce-9c4f-bfdf38c9a691)


And At the end, Turn off the Smart App Control

![5](https://github.com/Tmtmohseni/Tmtmohseni/assets/162871906/47597092-8628-48c5-82d4-572da7ac8664)
