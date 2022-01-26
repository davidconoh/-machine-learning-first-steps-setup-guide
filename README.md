# Machine Learning First Steps Setup Guide
This setup guide is for the **tutorial** at [Yonder Hacks](https://github.com/yonderhacks/machine-learning-first-steps).

## Getting Started
Before we kick start our learning journey, we would require you own a laptop running a recent version of any of the popular operating systems ([Windows](https://www.microsoft.com/en-us/windows), [Mac](https://www.apple.com/mac/), [Linux](https://www.linux.org/pages/download/)), or [**Raspberry Pi**](https://www.raspberrypi.com/) computer, an active **Internet** connection, and the following services to get you ready for an amazing experience:

- **Anaconda software**
- **GitHub account**
- **Git**
- **Python 3 libraries**
- **Extensions**

### - **Anaconda Software**
**Anaconda** is a powerful tool for data science and exploration enjoyed by an extensive community of developers and data scientists from across the world. It is supported on **Windows**, **Mac**, **Linux**, and **the Pi** with some caveats you will find out in this lesson. To get **Anaconda** up and running on your machine, head over to the Individual Open Source Edition [here](https://www.anaconda.com/products/individual) to download the latst **Python 3** version for your platform before getting started.

There is great support for [Windows](https://docs.anaconda.com/anaconda/install/windows/), [Mac](https://docs.anaconda.com/anaconda/install/mac-os/), [Linux](https://docs.anaconda.com/anaconda/install/linux/), and [the Pi](https://stackoverflow.com/questions/39371772/how-to-install-anaconda-on-raspberry-pi-3-model-b) to get it to work on your system if you need help. 

### - **GitHub account**
**GitHub** has been an amazing support for open projects on the web and we are going to take advantage of it to create our portfolio. Head over to **GitHub.com** and [Sign up](https://github.com/signup) for a free account or [Sign in](https://github.com/login) to your existing account if you already have one.

Don't be lazy now, you'll be glad you did after this lesson.

### - **Git**
Without **Git**, it is impossible to use **GitHub**. We will use this tool to manage the different versions and stages of developing our machine learning model.

Installing **Git** on **Windows** can be tricky, but we recommend [Git for Windows](https://gitforwindows.org/) for its **bash** support and this [guide](https://www.makeuseof.com/install-git-git-bash-windows/) provides wonderful setup instructions.

 **Git** preinstalled on most versions of **macOS** and **Linux**. However, if you are unable to find **Git** on your machine by typing the command `git --version` in your terminal, head over to [git-scm.com/download/linux](https://git-scm.com/download/linux) to get the latest version for your **Linux** flavor or [git-scm.com/download/mac](https://git-scm.com/download/mac) for **macOS**.

**Git** is installed on **Raspberry Pi** by default.

For first time setup, follow this [instructions](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup).

### - **Python 3 libraries**
If you followed the instructions and installed correctly the **Python 3** version of **Anaconda** (or **Miniconda** for the **Raspberry Pi**), open your terminal for **Linux** or **macOS** or Anaconda Prompt on **Windows** and enter `conda list` (`conda` if you're rinnung **Pi**). The output is a verbose list that begins somewhat like this:
```
# packages in environment at /home/<username>/anaconda3:
#
# Name                    Version                   Build  Channel
_ipyw_jlab_nb_ext_conf    0.1.0            py39h06a4308_0  
_libgcc_mutex             0.1                        main  
_openmp_mutex             4.5                       1_gnu  
alabaster                 0.7.12             pyhd3eb1b0_0  
anaconda                  2021.11                  py39_0  
anaconda-client           1.9.0            py39h06a4308_0  
anaconda-navigator        2.1.1                    py39_0
```
This confirms that you have all the necessary libraries for our sample project and ready to roll.

Enter `conda deactivate` in your terminal to deactivate **Anaconda** and `source ~/.bashrc` to reactivate it. (For **Windows**, it is `activate` and `deactivate` from the command-prompt).  You will see a `(base)` before your userprofile when it is active and the `(base)` will disappear when it is not.

### - **Extensions**
The **Anaconda** environment comes preloaded with a number of tools for data science projects. But, you can extend it's functions by installing from the interface other alternatives and environments that meet your needs. Free free to be creative.

## Next Steps
Thank you for following this guide. See you at the event. 🎉