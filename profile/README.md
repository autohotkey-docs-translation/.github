# How to contribute
1. Ask Ragnar-F (via [PM](https://www.autohotkey.com/boards/ucp.php?i=pm&mode=compose&u=108)) or joedf (via [PM](https://www.autohotkey.com/boards/ucp.php?i=pm&mode=compose&u=55)), or on the [forum](https://www.autohotkey.com/boards/) if you're not allowed to message someone directly yet, to get write access to a project. If a project does not yet exist for your language, it will be created.
2. Download and run [OmegaT](https://omegat.org/download#latest) (latest version recommended)
3. Click in the menu bar on Project > Download Team Project...
4. Enter `https://github.com/autohotkey-docs-translation/<repoName>.git` in the first input field and replace `<repoName>` with the repository name (e.g. v1-nl)
5. Specify your new local project folder in the next field
6. Click on OK

At some point during the synchronization you will be asked for your GitHub username and password. You only need to enter this information once. Due to security-related changes made by GitHub on August 13th, 2021, you will now need to enter a personal access token (PAT) instead of your GitHub password:
1. Open your [GitHub account settings](https://github.com/settings/tokens)
2. Click on "Generate new token"
3. Select "Generate new token (classic)"
4. Write something in "Notes" (e.g. autohotkey-docs-translation/v1-nl)
5. Select "No expiration" for Expiration
6. Check "repo"
7. Click on "Generate token"
8. Copy the string inside the green box and use this string as the password

For details, see [Creating a personal access token](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token). If you need to force the credential dialog to reappear, remove the old credentials under Options > Preferences... > Team > Repository Credentials in OmegaT.

That's it. Now you can translate as you like. Your new translations will be uploaded automatically on a regular basis and at various events such as save, close, etc. If you want to check the current translated state of the document, click on Project > Create Translated Documents and then on Project > Access Project Contents > Current Target Document. When you think it's ready for publishing for now, click on Project > Commit Target Files and let us know via PM, so we can publish the docs. If you have questions, feel free to ask us.

# Tips
- If a translation is identical to its source text, use "Register identical translation" (Ctrl+Shift+S or accessible from the menu bar or right-click menu) to mark it as translated instead of skipping it. This helps maintainability in the sense of going to the next untranslated segment (Ctrl+U); for example, if there is new text after a docs update.

# Tools
- [**OmegaT**](https://omegat.org/) - Free open-source translation memory tool, computer-assisted translation (CAT) software
  - [Google Translator without API key](https://sourceforge.net/projects/omegat-gt-without-api-key/files/) - Plugin for Google Translate service, without needing an API key.
  - [More plugins](https://sourceforge.net/p/omegat/wiki/Plugins/)
- [**Microsoft Terminology Translation**](https://www.microsoft.com/en-us/language) - Useful for when you need a computer-term in a different language. These are used my Microsoft themselves for things like Windows, Office, Skype, Xbox, Bing, etc.
  - You can download *.tbx glossary files here to help with CAT software: 
  https://www.microsoft.com/en-us/language/Terminology
- [**DeepL**](https://www.deepl.com/translator) - An online service that provides more accurate machine translations than other common services.
