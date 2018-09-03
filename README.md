# Django Code Challenge: GirlsGetGeeky Developer Community
## Due: 2nd October, 2018 or Earlier
#### This code challenge is due on the 2nd October, 2018 or earlier. 

## Simple Unchanging Rules
The code challenge is and will always be judged using the following criteria:
  - A Correct fork, branch and pull request
  - Using the GitHub Pull Request Time Stamp and correct code quality & structure, the first developer whose code runs successfully wins
  - Other developers who submit successfully MAY also get rewarded with secondary items
  - Code quality and structure will be evaluated
  - The order for pull requests will be followed, first come first win basis!
  - Do not share any code that you cannot opensource on the Git Repository as its open source and Africa's Talking will not be liable for any breach of intellectual property (if any) once shared on the platform.

## Terms and Conditions
You can participate on as many challenges as you wish:
  - Everyone can participate for secondary prizes, just ensure that you create your branch with your international format phone number. Airtime rewards will only go to countries we have AirTime APIs in.
  - Africa's Talking reserves the right to announce the winners
  - Africa's Talking reserves the right to reward the winners based on Africa's Talking Criterion
  - Do not share any code that you cannot opensource on the Git Repository as its open source and Africa's Talking will not be liable for any breach of intellectual property (if any) once shared on the platform.
  - Code Challenges are time bound - the time restriction is specified on the challenge
  - Additional rules MAY be provided on the code challenge and will vary for each challenge
  - You are free to use all manner of tools
  - Successive interviews for projects MAY be run to satisfy participating Africa's Talking Partners

## Code Challenge Bounty:
  - First Prizes: A pair of Pace Focus Headphones

## Task
In this code challenge you will be required to make a Django application that:
1. Implements authentication (User can login and logout)
2. The user can create a list of contacts and saves it to a DB of your choice
3. The user can send SMSs to the contacts using the Africa's Talking SMS API

### Task Workflow:
1. User logs in or signs up for the application
2. User is able to create a list of contacts saving their name and phone numbers
3. The user is able to create a message and select a list of contacts to send SMSs to
4. Once they hit send, the messages ought to be sent to the list of contacts specified
5. Ensure your service is accessible online. You can use the free tiers of [Heroku](https://www.heroku.com/)

# Working on the Code Challenge
1.Fork the code challenge repository provided.

2.Make a topic branch. In your github form, keep the master branch clean. When you create a branch, it essentially will be a copy of the master.

>Pull all changes, make sure your repository is up to date

```sh
$ cd DjangoGirlsCodeChallenge 
$ git pull origin master
```

>Create a new branch as follows-> git checkout -b [your_phone_number], e.g.

```sh
$ git checkout -b 25472XXXXXXX master
```

>See all branches created

```sh
$ git branch
* 25472XXXXXXX
  master
```

>Push the new branch to github

```sh
$ git push origin -u 25472XXXXXXX
```

3.Make changes to the fork following the Code Challenge provided.

4.Commit the changes to your fork.

5.Make a pull request to the DjangoGirlsCodeChallenge 
Repo.

### Additional:
1. See the online version of the code challenge [here](http://atdevoutreach.viewdocs.io/DjangoGirlsCodeChallenge/DjangoGirlsCodeChallenge/) to get acquainted.

2.  Check out the format for submitting your code [here](http://atdevoutreach.viewdocs.io/DjangoGirlsCodeChallenge/DjangoGirlsCodeChallengeSteps/)

## Resources
You can use the following resources to get you started on your way:
* [Starting on the Sandbox and Simulator](http://help.africastalking.com/website/how-to-get-started-on-the-africas-talking-sand-box)
* [Africas Talking's Python SDK documentation on GitHub](https://github.com/AfricasTalkingLtd/africastalking-python)
* [SMS Sending Documentation](http://docs.africastalking.com/sms/sending)
* [SMS Receiving Documentation](http://docs.africastalking.com/sms/callback)
* [Other Help articles](http://help.africastalking.com/sms)
- More on [Logging in, Signing up/Registration, Verifying/Activating your account, Managing Teams and applications](http://help.africastalking.com/website)
- Videos on getting started [on the Africa's Talking Sandbox](https://www.dropbox.com/sh/qq086503d5zaq7l/AADEo-oazNF_PgYIPRjPpeCua?dl=0)


## About Africa's Talking Code Challenges
Please read the overview for all code challenges [here.](http://atdevoutreach.viewdocs.io/DjangoGirlsCodeChallenge/)

## Get Support on the Africa's Talking Slack
In case you have any questions, join our Slack [here](https://slackin-africastalking.now.sh/)
