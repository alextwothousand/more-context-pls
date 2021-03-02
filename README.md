# more-context-pls

  ## Preamble
  You're in a help forum / communication application and you decide to ask for help. You're lost for words, so you are unsure of how to formulate your question.
  You decide to go with something simple.

  ```
  I have a problem compiling my script.
  ```

  A simple question like this may seem simple to answer, but, notice how you've provided no context at all.
  This doesn't help either party, causing frustration and misunderstanding from and to both sides.

  ## The first steps
  As you are not the only human being on this planet, your question can likely be answered, without having even been asked it at all!
  Input your question into Google, or an alternative search engine, and a result will likely pop up.

  ```
  How can I modify my Visual Studio 2019 Project Solution File to link a library like OpenSSL?
  ```

  A question, such as the above, is an example of a poor search engine query. Search engines are engines, they are not humans - they work based off of keywords. Certain keywords trigger certain search results, and that's how you get your free Dominoes pizza.

  Abstracting your question to remove the irrelavent information would be the first step.

  ```
  How can I modify my Visual Studio Solution File to link a library?
  ```

  Already looking better! The version of Visual Studio wouldn't matter a huge amount, as the general UI/UX has been kept the same for a while.
  What library we want to link is also irrelavent. The steps are the same for all libraries.

  Another round of abstraction. Dont ask to ask style.

  ```
  Modify my Visual Studio Solution File to Link Library
  ```

  A lot better. But this can still be further abstracted.

  ```
  vs project link library
  ```

  Impressive, right? 4 words. Give it a go! [Click](https://lmgtfy.app/?q=vs+project+link+library)

  ## What if I cannot find my question online?

  Don't fret. You can do what other's have done and ask a question.
  Just ensure you've provided relevant context in relation to your query.

  ## How can I provide context related to my question?

  You should provide information such as (in the case of C);
  * What compiler and what version of that compiler you are using;
  * Are you using any build systems?;
  * Build errors as **text** - see [this](https://textnot.pictures).

  It would be useful if you also provided;
  * Your operating system and architecture;
  * The operating system and architecture you are targeting.

  Here's an example of a decently-well formulated question.

  ```
  My script fails to compile, outputting an error LNK2019.
  The library I'm trying to link is OpenSSL.

  I'm using MSVC on Windows 10 x64, targeting amd64.
  I'm building for Windows only, using the CMake build system.
  ```

  This provides the person answering your question sufficient context about your query, making it easier for all parties.

  ## The end!

  I hope you enjoyed the read. Apologies for the iffy tone, this really was just a 1 AM vent-type post.
  If you wish to contribute, please feel free.
