# How-To-Install-Spark-MacOS

Beginner's Guide to installing Apache Spark for Machine Learning and AI on MacOS using Homebrew

Macs are great but they can be buggy and sometimes have weird commands and configuration problems. This is the best way that I have found to install and run Spark without any weird bugs or configuration issues.

This guide is meant to help a total command-line/terminal noob install and run Apache Spark with 
no prior command-line experience.

First off you need to install a package manager on your MacBook. A package manager is essentially an all-in-one tool that downloads, configures, and installs programs for you on your computer. Homebrew is a great choice.

1. On your computer, click on the magnifying glass and type in "terminal", this will open a console, you know, the thing hackers use ;).

2. First, you need to set up your console for development by installing Xcode command-line tools. You really need this Xcode command-line tools include common development and programming tools, utilities, and compilers, including make, GCC, clang, perl, svn, git, size, strip, strings, libtool, and cpp. Type the following command and hit enter:
 
 ```xcode-select --install```

3. To install your package manager, Homebrew, type the following command and hit enter:

```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" ```
  
4. After the installation is complete we need to make sure that homebrew installed correctly by entering: 
  
```brew doctor```

5. Next were going to install a Homebrew extension that speeds up Homebrew and will allow you install graphical apps with Homebrew. Enter: 

```brew install caskroom/cask/brew-cask```

6. Next install python(python is default installed on MacBooks, this is just to make sure everything is OK.) Enter:

```brew install python```

7. Now we can finally install Spark. Enter:

```brew install apache-spark```

8. We're almost done! Lets make sure everything is up-to-date, enter:

```brew upgrade```

9. Launch in your terminal Spark by entering:

```pyspark```

YOU'RE DONE!

Anytime you want to run Spark simply open the terminal up and enter:
```pyspark``` and you'll be good to go!

Good luck!
