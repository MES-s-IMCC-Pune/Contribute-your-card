# [Contribute your card](https://mes-s-imcc-pune.github.io/Contribute-your-card/)
This repository is created for beginners (students) to learn how to contribute to open source projects on github by learning how to raise the Pull Request. (inspired from Syknapse's[ repositry](https://github.com/Syknapse))

## Prerequisite

1. Have a GitHub account (if not then you can refer to [this](https://dev.to/iatharva/how-to-create-github-account-for-beginners-52k8) to create your github account)
2. Have git installed on your local machine (if not you can download it from [here](https://git-scm.com/downloads))
3. Have a IDE/Text editor (If you use [VS Code](https://code.visualstudio.com/ 'Visual Studio Code website') it comes with integrated Git and allows you to do what we need straight from the editor)

## Steps for contributing (To Add your card)

- ### Fork this repository
  - The objective here is to make a copy of this project and place it in your account.
  - Make sure you are on the [main page](https://github.com/MES-s-IMCC-Pune/Contribute-your-card) of this repo.
  - Fork the repository by clicking on fork button seen in right corner of the screen (image)
  - ![Screenshot](https://user-images.githubusercontent.com/25875102/151494138-9c0d85f9-e696-46a7-9362-cc8f813a6f26.png)
  - You now have a complete copy of the project in your own account.

- ## Clone the repository
  - Now we want to make a local copy of the project. That is a copy saved on your own machine.
  - Open any folder where you want to clone the repository.
  - Then you can right click and select Git Bash here option
  - ![Screenshot (38)](https://user-images.githubusercontent.com/25875102/151494492-07d75476-9673-4fcb-94ec-05c29536524f.png)
  - then type ``` git clone yourlink ``` and press enter
  - Replace yourlink with the link of your repository which you can get as shown in image below
  - ![Screenshot (41)](https://user-images.githubusercontent.com/25875102/151505001-9554ac2c-82e5-49e2-93a5-2250ace8d67a.png)


- ## Create your branch
  - Then you will need to type ``` cd Contribute-your-card ``` and press enter to go to that folder/repo.
  - and type ```git checkout YourName-dev ``` and press enter example: ``` git checkout Atharva-dev ```
  - This will create a branch named "YourName-dev" and switch to that branch.

- ## Add your card 
  - Once this all is done you can open the index.html file in your preferred IDE/Text Editor
  - and Copy the Template shown in the Image.
  - ![Screenshot (39)](https://user-images.githubusercontent.com/25875102/151495347-51f984e3-400b-48ee-b15c-6edcb8e62aa2.png)
  - Paste it below the code shown in image by having one space between the above code. 
  - (NOTE - YOUR CARD MUST BE ON THE TOP and BELOW THE TEMPLATE and COMMENTS)
  - ![Screenshot (40)](https://user-images.githubusercontent.com/25875102/151495500-c6af9d63-7516-476b-9ffc-b32d649f56db.png)
  - Make the changes by adding your information to the card.
    - Replace name by Your name by your own name.
    - Roll no with your own roll no (your college roll no) (you can leave it blank if you dont have one) 
    - Replace Class with your class followed by college name (example: SY MCA, MES IMCC) (you can leave it blank if you dont have one) 
    - You can share your socials by modifying the below snippet which is present in template (You can add multiple socials by modifying ``` <i class="fab fa-twitter">``` with your desired social media (example : ``` <i class="fab fa-linkedin">```) )
    -```<p class="contact">
            <i class="fab fa-twitter"></i>
            <a href="www.twitter.com" target="_blank">Your handle</a>
          </p>```
    - Add your three favourite (programming) languages (by modifying the title and text)
    - Last Step would be modifying the start and end title with yourName i.e. ```<!-- ________ *TEMPLATE: MAKE A COPY* Contributor card START ________  -->``` ```<!-- ________*END TEMPLATE* Contributor card END ________  -->``` with your own name (example: ```<!-- ________ *Atharva's card START ________  -->``` ```<!-- ________ *Atharva's card END ________  -->```).
   - SAVE THE FILE.

- ## Commit the changes
  - Go to the cmd (opened previously) or you can open new cmd with the location of your repository.
  - Check the branch by executing ```git branch``` you should see  your branch with asterisk in front of it example :```*YourName-dev```
  - Which means the branch in which you are present is your.
  - Now type ```git add index.html``` and press enter which will add your file to staging area
  - Once that is done, to commit the file, type ``` git commit -m "YourName's card added" ``` and press enter.
  - after that type ``` git push --set-upstream origin BranchName ``` and press enter (example : ```git push --set-upstream origin Atharva-dev```).
  - CHANGES FOR PUSHED TO YOUR REPO.

- ## Check if changes are commited
  - Go to your forked repository which can be seen on your profile.
  - Or when you got to github.com you can click on your profile and go to your repository to open it.
  - ![Screenshot (42)](https://user-images.githubusercontent.com/25875102/151505507-eb6b68f1-4c85-4124-af5f-7c878238bab9.png)
  - and then you can check if the changes your commit is visible or not
 
- ## Raise a Pull Request
  - Click on the compare & pull request button visible as shown below
  - ![Screenshot (44)](https://user-images.githubusercontent.com/25875102/151506747-7b3a645d-b80d-44d6-b7b0-9f9a222282e5.png)
  - Add appropriate title which should like below
  - ![Screenshot (45)](https://user-images.githubusercontent.com/25875102/151506944-afdacb11-7759-444f-ba29-a2f48a779dc9.png)
  - CLICK ON CREATE PULL REQUEST
  
- ## Congrats on creating a successful PR
  - Now you should see page as below
  - ![Screenshot (46)](https://user-images.githubusercontent.com/25875102/151507672-77642da0-ea2a-4bb8-9f5b-efdf0533bfc0.png)
  - Once your PR is reviewed and merged your PR page will look like this 
  - ![Screenshot (47)](https://user-images.githubusercontent.com/25875102/151507731-afe4273d-2a52-4bd4-8c59-00e63e857b9e.png)

Now you know how to raise a PR :) 
You can check your card [here](https://mes-s-imcc-pune.github.io/Contribute-your-card/)
