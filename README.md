# globitek_apex
# Project 5 - Encryption

Time spent: **X** hours spent in total

## User Stories

The following **required** functionality is completed:

1\. Symmetric Encrypt/Decrypt
  * [X]  Required: Repair the symmetric encrypt and decrypt code

2\. Encrypted Message 1
  * [X]  Required: Decrypt the government message
  * [X]  Required: Encrypt a response and include in this README
  
  Encrypted Message: 8oEaKxTYKX+f/uzBw2P1YBmp7EiZ9A1Fl+/klhDfa9IKphSDub4N58iNcHvCO9zYGT/U0xDChgKFBt34VYsgVqZVqWN4WDYRpAyVQ/m0KDiJbtTa9zo3ftJH5ehdVrbOK62Tvj/BWUH2EFUuHXC3/g==

  Decrypted Message: I heard about your current situation. Do you know who hacked APEX? -- The Chairman
  
  Response: It was Dark Shadow Agents who hacked us.  P.S. We might have a mole. --agent99
  
  Encrypted Response: v7a+GV3SgBhsGkNfuLV/XGF3YTEH3Y6bNWp6rnsvePbtVaXlmzlA3SAO/rtCNvaH0t8LjgBPGQlZFvobw3/6LZW9p+7WtK/ic2/UEfnedocROjolGKD47I69ilArPGcd

3\. Generate Public-Private Keys
  * [X]  Required: Repair the key generator code
  * [X]  Required: Generate keys for "johnsteed" and add him to the Agent Directory

4\. Asymmetric Encrypt/Decrypt
  * [X]  Required: Repair the asymmetric encrypt and decrypt code

5\. Create/Verify Signature
  * [X]  Required: Repair the create and verify signature code
  
6\. Encrypted Message 2
  * [X]  Required: Decrypt the message
  * [X]  Required: Verify the message
  * [X]  Required: Include a response message in this README
  
  To: agent99
  From: sydneybristow
  Subject: Encrypted and Signed Message
  Body:
  
  V13zGoKin0/0qDLnOxhJXp5wrcijADcH7LxPRX7OytfrIgVU95oYWFT/bYpCs39b3Wt2mCqTqW8wOrC02UyHyWll6+KcTm0lpLgE+Of4lEYsGQWKZtpOyuejkwu/5+sKzRPeb7 3i03c/RpHXDhjlTNCfhKwmNEEmSYZjoFLu59NKhOWO7eFVUPWH82RUPEqMrrxEUik844agENr4yhXYoehSqYM/mZpgHoN8dfu+EzTZxpy2j5bBMECfLPVdR9u7OXngSztYqhBy2okuwDBkId4/4TXcUM7ioYTUMki3j3r/JIXNpb5qJtkhCN6fDA2Kowz91R5bR6rkrRRjzxMn5A==

  Cannot access APEX from this location. Send new agent codename and public key so I can contact. Encrypt response to protect codename. Include signature to verify identity and message integrity. -- sydneybristow

  Signature: t6Swk/V4PaCpTkvQRKuYVLh36a/8j7eLVJQHdh9Rkc1iBPPM2LVcu+CkqOvtnGsndnShHhF0zUA1QgW5727dWMZ0LebGveUp8g7TCvnu/XDm3HcHp4BpGi7m+y7kZPzSWN7fsWR/pR28iV9OXnnw0dTP7VXXVaZH5Y8LydZoUPNq36VKLx7d4wGJ1zUEeIqjZi3W8HtzJCt8H2vIXOZjtoYwwtszcEHcNGmnbetbCtAOXgM0fZMrsQkIPQgANJlRV+La60VZsFmK2uvu/hzL1SBmY4miu3rUs2ybjEeploxC/sg2yBjEGpv9pX+kmnyW0pFRdLwaW68bRD7yiLlY5Q==
  
  To: sydneybristow
  From: agent99
  Subject: Encryped and Signed Response
  Body: 
  
  Your new codename will be blackfalcon.  Rendezvous with team at extraction point.  Good luck. --agent99

  c5SdcDsyQ9cithDjs9A4UthMQm0VeVLiq/iQZs0kz3pANK1ZkCkQ76smthgyZou/Wy5tf//9QZiug0H6HHIgVM8CTW/TWqsIYP43f66Wn0b5Mjj5bK1sdayQfadY9ymx1j/ahHhNk/oUBglSrZig6xmJAY98/kyUKtAnmUGtPDNDM6fmqitlob5KOZawYvKODYhh57fkCwAPRmpgyZbGDQ1Nqi+L+N7Sy1tX2fGR/mDXzrdoo6pOA8FZazFCiIE7dgA9tjGbX2IU/GngWm5dLEYm68YTZaCso1hag/g3Yasv1SIoYRrwOF0HwW7Nk4lure3rPt4SvAkdCCEy4FsBrQ==
  
  Signature:
  vC/Yu2b/DRrzkae3q8s5nLgTi5VwwdPvew1Ze2Sy8DQ1RPceE+Ol3B9t5TfVMHjfm2+e39i/6jIIFCwJD9q5e07guiaQ5PFqPI8aPlFs3uv9GSjEsDxkoLuJgwSTVYMiYQT4OQbd6TQCX3uao+aIrBJQtLn77WAlxZvknX9MAmrmMYIcemsGYQEJ5v/azn3pPTZwEPPEWmvHemLqqKaK1Dzx7tHOVyCnt5E8IOzgl3N2wiEW2lLDSjMcXbH/A+AY0Ccqd3QuK+kOrB/YMSN+Z73B3FpjqrSBJdW3nJ728E7YXnQUocxBHU38McxRonBwU5VO/MU5byQCoXgVQNEnwg==


7\. Agent Messages
  * [X]  Required: Repair the dropbox code
  * [X]  Required: Repair the messages area
  * [X]  Required: Display encrypted messages for all agents
  * [X]  Required: Messages indicate whether the message signature is valid
  * [X]  Required: Your messages are automatically decrypted

8\. Identify the Double Agent
  * [X]  Required: Decrypt as many email messages as possible
  * [X]  Required: Identify the double agent: Natasha

The following objectives are **optional**:

* Bonus Objective 1\.
  * [ ]  Track down the bugs in the code and fix them.

* Bonus Objective 2\.
  * [ ]  Write a report of your discoveries (longer than 300 characters).
  * [ ]  Compose a secure email for sending over an insecure network.
  * [ ]  Include the email with your encrypted report in this README.

* Bonus Objective 3\.
  * [ ]  Add a "Create/Verify Checksum" section to the Encryption Tools area.

* Advanced Objective 1\.
  * [ ]  Add support for other symmetric algorithms.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## License

    Copyright [2017] [James Han]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
