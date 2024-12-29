# Mass Any Shell or Uploader To File Uploader

**Overview:** The File Upload Tool is a powerful utility designed to streamline the process of uploading files to multiple URLs. It automates the task of finding suitable forms on web pages that support file uploads, submitting the chosen file to these forms, and logging the successful uploads for future reference. This tool is particularly useful for bulk file uploads or for testing file upload functionality on multiple websites at once.

**Key Features:**
  + Bulk Upload Capability: The tool can read a list of URLs from a file (list.txt) and attempt to upload a specified file to each of those URLs. This makes it ideal for use cases like automated testing or content distribution.
  + Randomized Filenames: For added security and to avoid detection, the tool generates random filenames for each file upload. This prevents file name conflicts and ensures that each upload is unique.
  + Log File Generation: After each upload attempt, the tool logs the results in a file named success.txt. This log file is appended with new results, so previous data is preserved, allowing users to track upload success over time.

**How It Works:**
  + The tool prompts the user to provide a path to a list of URLs (list.txt).
  + It then asks for the custom file specified by the user.
  + The tool attempts to upload the chosen file to each URL, checking if the page contains a form with file upload functionality.
  + For every successful upload, it logs the result in "Result/success.txt".

**POC:**

![image info](https://raw.githubusercontent.com/cpkarma/img/refs/heads/main/shell2file/Screenshot_1.png)
