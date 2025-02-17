# yuiget-web
A simple bash script for downloading websites/pages using wget. 
![c072aec207ee217caa1dda48ebba4f4fda16eafdd91a9aa8d692edc20b2b18e5](https://github.com/user-attachments/assets/24c95902-d383-484b-b39b-77a7a7c99375)

Yui will download your files into your desired location. 
She'll do her best download enough content from the site to keep the downloaded copy as close to the original as possible, and change links to point to your local copies if you supply her with multiple pages that link together.
Yui will also organise sites into folders based on the current date, so you can keep an archive of old site versions whilst you continue to download updated snapshots of the site without having to worry about it overwriting the information.
You can also guide her with options to try and improve your results depending on the site, and decide whether you want to recursively download content from links on your chosen page(s).
## Installation
* Clone the repository to your preferred location.
* Run ./install.sh to create a symlink in your ~/.local/bin/ directory.
* Simply git pull to update (if that ever happens).
* If you move around the files, you may need to delete the symlink and re-run the install script.
## Usage
Simply type yuiget-web into your terminal followed by the options and arguments you'd like to use. Use -h for help.
