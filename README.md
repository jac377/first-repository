# Purpose

The purpose of this reposityory will be for me to create and practice documenting my learning through the course of CS 260. <br> 
I willl annotate commands, or important information that I will like to have handy, so I don't have to be search for it. I will divide it per console/environment, so it is easier to find what I am looking for.

## Important links
Instructions to [C S 260 - Web Programming](https://github.com/webprogramming260/.github/blob/main/profile/instructionTopics.md#readme) <br> 
Editing instruction for [GitHub HTML Formatting](https://github.com/webprogramming260/.github/blob/main/profile/essentials/devAndProd/devAndProd.md)

## IP Address to my new serve and DNS
3.129.226.38
mindlydrinking.click

## How to acces my Remote Server using Console
ssh -i ~/keys/[file name of key] ubuntu@[domain name] <br>
exit  "Will exit from the remote machine"

##  SHA
SHA is the unique ID for a specific version, so this can be used with 'git checkout' and this ID.

## Important things I have learned
We use AWS cloud to create our server.
Route 53 is used for creating DNS and attaching it to my IP address of my server. Remember that I need to create records so people can access my server with the DNS. Use * for any subdomain (appended before the root domain), so it can lead to the main server.

## VI Commands
- :h "Help"
- i "Insert or edit file"
- u "Undo"
- CTRL-r "Redo"
- / "Search for text after /"
- v "Select text"
- y "yank or copy"
- p "paste clipboard"
- :w "Save file"
- :q "Quit" or :q! "To quite without saving"

You can also combine them, such as :wq, which will save and quit.