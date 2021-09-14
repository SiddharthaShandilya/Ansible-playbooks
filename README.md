HI there


# Ansible-playbooks

[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](http://forthebadge.com)   [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)      [![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://forthebadge.com)


<!--
The application uses cnn for training new model for recognizing a face as well as train a new face followed by allowing user for access or use multiple function.



<!-- #`oh-my-zsh` with `powerlevel9k` theme and `powerline nerd-font + awesome-config` font with the `Solarized Dark` color theme. 

 ![image](https://user-images.githubusercontent.com/17109060/32149040-04f3125c-bd25-11e7-8003-66fd29bc18d4.png)

*If you're interested in knowing the powerlevel9k configuration to get this prompt, have a look at [this gist](https://gist.github.com/athityakumar/1bd5e9e24cd2a1891565573a893993eb).*



# Table of contents

- [Usage](#usage)
- [Demo](#demo)
- [Installation](#installation)
- [Recommended configurations](#recommended-configurations)
- [Custom configurations](#custom-configurations)
- [Updating](#updating)
- [Uninstallation](#uninstallation)
- [Contributing](#contributing)
- [Future Scope](#future-scope)


# Usage

[(Back to top)](#table-of-contents)

📌 When it recognize your face then -  

👉 It send mail to your mail id by writing this is face of your_name.  

👉 Second it send whatsapp message to your friend, it can be anything.  

📌 When it recognize second  face, it can be your friend or family members face. 

👉 Creates EC2 instance in the AWS   

👉 Creates 5GB EBS volume and attach it to the instance. 



</br>

# Demo
[(Back to top)](#table-of-contents)

📌 Train model to detect a face

_______________________________________________________________________________________________________

👉 Here is a simple demo of the working model


![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/61656756/132636457-acc004a3-e5e4-4267-a75f-b7bd3ddcfdca.gif)

_______________________________________________________________________________________________________

📌 The next step is to launch ec2-instance and and send what'a app message when a face is recognized.

_______________________________________________________________________________________________________

![face_2](https://user-images.githubusercontent.com/61656756/132645279-d5277de4-b712-47a0-829b-857e16034f93.jpg)


👉 I have used terraform to access and launch an ec2-instance.
_______________________________________________________________________________________________________

📌 After your ec2-instance is launched the code will send a message to your what's-app 

_______________________________________________________________________________________________________

![face_](https://user-images.githubusercontent.com/61656756/132645273-6dae1f6c-4230-4c06-9acb-15a032ad3945.jpg)


👉 In order to send a what's-app message i have used twilio.rest library. Enter your phone number as well as your clients number.

_______________________________________________________________________________________________________





# Installation


[(Back to top)](#table-of-contents)

1. Install git (preferably, version >= 2.0) and python (preferably, version >=3.6)
 [(windows)](https://www.maketecheasier.com/install-git-bash-on-windows/)
 For Linux :
 ```bash
    sudo yum instal git -y
    sudo yum install python -y
 ```
 
2. Copy the github url from the repository : 

 ```bash
 https://github.com/SiddharthaShandilya/Face_recognition_task_EC2-What-sAPP.git
 ```

3. Select a Directory in local system and use 

  ```bash 
  git clone https://github.com/SiddharthaShandilya/Face_recognition_task_EC2-What-sAPP.git           
  ```

    *Note for `git clone command`  Please make sure that you have proper internet connection. *

    *Note for `python` Please try to anaconda for running the app.*  

4. Create a seperate virtual environment to avoid conflict between python libraries :
    ```bash
    python3 -m venv new-env 
    ```

5. Activate the virtual env: 👉 [(click Here)](https://www.programshelp.com/help/python/activate_virtual_environment_python_windows_10.html)
6. Install all the libraries for the application.
```bash
pip3 install -r requirements.txt
```

6. Have a look at [Recommended configurations](#recommended-configurations) and [Custom configurations](#custom-configurations).


</br></br>


# Recommended configurations

[(Back to top)](#table-of-contents)

<!--

1. To add some short command (say, `lc`) with some flag options (say, `-l`, `-A`, `--sd`) by default, add this to your shell configuration file (`~/.bashrc`, `~/.zshrc`, etc.) :
    ```sh
    alias lc='colorls -lA --sd'
    ```

2. For changing the icon(s) to other unicode icons of choice (select icons from [here](https://nerdfonts.com/)), change the YAML files in a text editor of your choice (say, `subl`)

    ```sh
    subl $(dirname $(gem which colorls))/yaml
    ```

</br></br>
-->

# Custom configurations

[(Back to top)](#table-of-contents)

<!--
You can overwrite the existing icons and colors mapping by copying the yaml files from `$(dirname $(gem which colorls))/yaml` into `~/.config/colorls`, and changing them.

- To overwrite color mapping :

  Please have a look at the [list of supported color names](https://github.com/sickill/rainbow#color-list). You may also use a color hex code as long as it is quoted within the YAML file and prefaced with a `#` symbol.

  Let's say that you're using the dark color scheme and would like to change the color of untracked file (`??`) in the `--git-status` flag to yellow. Copy the defaut `dark_colors.yaml` and change it.

  ```sh
  cp $(dirname $(gem which colorls))/yaml/dark_colors.yaml ~/.config/colorls/dark_colors.yaml
  ```

  In the `~/.config/colorls/dark_colors.yaml` file, change the color set for `untracked` from `darkorange` to `yellow`, and save the change.

  ```
  untracked: yellow
  ```

  Or, using hex color codes:

  ```
  untracked: '#FFFF00'
  ```

- To overwrite icon mapping :

  Please have a look at the [list of supported icons](https://nerdfonts.com/). Let's say you want to add an icon for swift files. Copy the default `files.yaml` and change it.

  ```sh
  cp $(dirname $(gem which colorls))/yaml/files.yaml ~/.config/colorls/files.yaml`
  ```

  In the `~/.config/colorls/files.yaml` file, add a new icon / change an existing icon, and save the change.


  ```
  swift: "\uF179"
  ```

- User contributed alias configurations :

  - [@rjhilgefort](https://gist.github.com/rjhilgefort/51ea47dd91bcd90cd6d9b3b199188c16)

-->
</br></br>

# Updating

[(Back to top)](#table-of-contents)

Want to update to the latest version of `chat_app`?

<!--
```sh
gem update colorls
```
-->


</br></br>

# Uninstallation

[(Back to top)](#table-of-contents)

Want to uninstall and revert back to the old style? No issues (sob). Please feel free to open an issue regarding how we can enhance `chat_app`.

<!--
```sh
gem uninstall colorls
```
-->

</br></br>

# Contributing

[(Back to top)](#table-of-contents)

Your contributions are always welcome! Please have a look at the [contribution guidelines](CONTRIBUTING.md) first. :tada:


</br>

# Future Scope
[(Back to top)](#table-of-contents)

Adding Voice chat app will make it more user friendly





-->
