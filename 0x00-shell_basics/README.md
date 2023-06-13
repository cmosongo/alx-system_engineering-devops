
<h1>Shell Basics README</h1>
<p>This README provides a brief overview of shell basics, including navigation, file manipulation, working with
    commands, and useful keyboard shortcuts.</p>
<h2>What Is "The Shell"?</h2>
<p>The shell is a command-line interface that allows users to interact with the operating system through text-based
    commands. It provides a way to execute various tasks, manage files and directories, and run programs.</p>
<h2>Navigation</h2>
<ul>
    <li><code>cd [directory]</code>: Change the current directory to the specified directory.</li>
    <li><code>cd ..</code>: Move up one level to the parent directory.</li>
    <li><code>pwd</code>: Display the current working directory.</li>
</ul>
<h2>Looking Around</h2>
<ul>
    <li><code>ls</code>: List files and directories in the current directory.</li>
    <li><code>ls -l</code>: List files and directories in long format, showing detailed information.</li>
    <li><code>ls -a</code>: List all files and directories, including hidden ones.</li>
</ul>
<h2>A Guided Tour</h2>
<ul>
    <li><code>clear</code>: Clear the terminal screen.</li>
    <li><code>echo [text]</code>: Print the specified text to the terminal.</li>
    <li><code>date</code>: Display the current date and time.</li>
</ul>
<h2>Manipulating Files</h2>
<ul>
    <li><code>touch [filename]</code>: Create a new file with the specified name.</li>
    <li><code>cp [source] [destination]</code>: Copy a file from the source location to the destination location.</li>
    <li><code>mv [source] [destination]</code>: Move or rename a file from the source location to the destination
        location.</li>
    <li><code>rm [filename]</code>: Remove a file permanently.</li>
</ul>
<h2>Working With Commands</h2>
<ul>
    <li><code>command1 &amp;&amp; command2</code>: Execute command2 only if command1 succeeds.</li>
    <li><code>command1 || command2</code>: Execute command2 only if command1 fails.</li>
    <li><code>command &amp;</code>: Run a command in the background.</li>
    <li><code>Ctrl+C</code>: Terminate the currently running command.</li>
</ul>
<h2>Reading Man pages</h2>
<ul>
    <li><code>man [command]</code>: Display the manual page for the specified command.</li>
    <li>Press <code>q</code> to exit the man page viewer.</li>
</ul>
<h2>Keyboard Shortcuts for Bash</h2>
<ul>
    <li><code>Ctrl+A</code>: Move to the beginning of the command line.</li>
    <li><code>Ctrl+E</code>: Move to the end of the command line.</li>
    <li><code>Ctrl+U</code>: Clear the command line.</li>
    <li><code>Ctrl+R</code>: Search command history.</li>
</ul>
<h2>LTS</h2>
<p>LTS stands for Long-Term Support. It refers to specific versions of software or operating systems that receive
    extended support and updates for an extended period, typically several years. LTS versions are recommended for
    stability and long-term use.</p>
<h2>Shebang</h2>
<p>A shebang, also known as a hashbang, is a character sequence at the beginning of a script file that specifies the
    interpreter to be used for executing the script. It typically looks like <code>#!/bin/bash</code>, indicating that
    the script should be run using the Bash shell.</p>
<p>Feel free to modify and expand upon this README to suit your specific needs.</p>

