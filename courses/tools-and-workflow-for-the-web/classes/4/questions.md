## Part 1

## Introduction
Use this document as a starting point for Part 1 of the Class 4 exercise. Answer the each of the questions below and either:
  - Attach this document to your exercise submission email.
  - Or copy-and-paste the contents of this document into your submission email.

<h1> JR Maschietto's Answers</h1>

## Questions
1. Write the command (or commands) that will display the following message 'Hello from the command line.'<br>
<b><code>echo Hello from the command line</code></b>

2. Write the command (or commands) that will create a file named 'hello-world.txt'.<br>
<b><code>touch hello-world.txt</code></b>

3. Write the command (or commands) that will create a folder named 'my-new-folder' in current directly.<br>
<b><code>mkdir my-new-folder</code></b>

4. Write the command (or commands) that will attempt to delete a folder named 'my-nonexistent-folder' and display the following message when the commands fails: 'Whoops, cannot delete a folder that does not exist'.<br><b><code>rmdir my-nonexistent-folder || echo 'Whoops, cannot delete a folder that does not exist'</code></b>

5. Write the command (or commands) that will navigate to your desktop, and then to the parent folder.<br><b><code>cd ~ && cd ..</code></b>
<i>For a more "visual" command:</i> <b><code>cd ~ && echo "- You are now on:" && pwd && cd .. && echo "- And now you are on:" && pwd</code></b>

6. Write the command (or commands) that will tell you the location of the Z Shell <i>( Mine is bash )</i>.<br><b><code>which bash</code></b>
