# leetcodeSubmissionDownload
A python Script to download Leetcode submissions

##Steps To follow to download your leetcode:
1. Login to [leetcode](https://leetcode.com/) account on your default browser
2. Get your session Id for leetcode.com from Browser. If you don't know how to get your session ID then follow [This Link](https://code.google.com/p/procurement/wiki/LoginWithSessionID#How_to_retrieve_the_value).
3. Create a folder to save your leetcode codes. ( say leetcodeDownloads )
4. Keep the downloaded leetcode.py into that folder.
   Then directory structure should be like this

   ```
  leetcodeDownloads
  |-- leetcode.py
  |
  ```
5. Replace PHPSESSID field in leetcode.py file with your session ID (copied in step 2)
6. run file as 'python leetcode.py
7. wait for all submssions to download.
8. Program will finish with successfully with the messege "Program finished with all your submissions have been saved"
9. The final directory structory would be something similar to this.

  ```
  leetcodeDownloads
  |-- Add and Search Word - Data structure design.cpp
  |-- Add Digits.cpp
  |-- Add Two Numbers.cpp
  |--....
  ```

##Features:
1. It will download only your latest accepted submission for particular code.
2. Assumption that your all submssions are available withing 500 pages of submissions.
3. Check [https://leetcode.com/submissions/500/](https://leetcode.com/submissions/500/) this link and verify if it showing  "No More Submissions."
3. The Source code is forked from original contributor's gist which is available at: https://gist.github.com/jw2013/8297202
