# Onboarding Documentation
Please read the following documentation first. This will help set you up for the work environment. This documentation will cover most of the first time configs and setups, and will give you a brief explanation on different topics.

# Setup
## Software
Make sure you have installed the following software with the correct version.
1. Git 2.x^ (alternatively, you can use [SourceTree](https://www.sourcetreeapp.com/))
	To check, `git --version`
2. Node 14.16.x
	To check, `node --version`
3. PHP 7.4.x
	To check, `php --version`
4. Composer 2.x^
	To check, `composer --version`
5. MySQL 5.7
	To check, open `http://localhost/phpmyadmin` and find your version.
	If you use the CLI version of MySQL, do `mysql --version`
6. [Vuejs Devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en)
7. Skype `latest`

**Note**: Instead of manually installing PHP and MySQL, you can also install [XAMPP](https://www.apachefriends.org/download.html) which already comes with both. Just make sure that after installing XAMPP, check your PHP and MySQL versions if they match the requirements above.

## Email
You will be given 2 email addresses and passwords.
<br/>
Example:
tech1@sumomedia.co <br/>
tech1.sumomedia@gmail.com <br/>

You can open your sumomedia.co email address at https://sumomedia.co/webmail. All emails sent to your sumomedia account will also be mirrored in your GMail account. So most of the time you will only need to open your GMail account.

## Setting up Git
Once you have opened your email address, you will receive an invitation to the bitbucket workspace. Bitbucket is where we store the remote repository, very much similar to GitHub.

Open your invitation link and create your Bitbucket Account. After creating the account, you should be able to see the repositories under the SumoMedia workspace.

In your Git application, do the following:
```git
git config --global user.name "<your name here>"
git config --global user.email "<your email used in bitbucket here>"
```

# Tech stack
Currently, we are working on two types of products. Websites and Web Apps. Each has a different way to setup, so read along for instructions.

## Websites
The websites are using a native PHP for backend and native HTML, CSS and JS for the frontend.

### Setting up
Please refer to [Darryl's Knowledgebase](#) for setting up the websites. The whole project is usually under one repository

## Web apps
The Web Apps are using Laravel(PHP) for the backend, and Nuxt(JS), which is a framework for Vue, and Vuetify. The projects are usually separated as backend and frontend repositories.

Other tech we are using: 
- **Vuex** - state management and caching.
- **Axios** - HTTP client, asynchronous calls to the server.

### Setting up
//

## References
Please visit these documentations for references on the tech stack.
- [PHP](https://www.php.net/docs.php)
- [HTML CSS and JS](https://developer.mozilla.org/en-US/docs/Web)
- [Vue](https://vuejs.org/v2/guide/)
- [Nuxt](https://nuxtjs.org/docs/2.x/get-started/installation)
- [Vuetify](https://vuetifyjs.com/en/introduction/why-vuetify/#why-vuetify3f)
- Vuex
	- [Vue Documentation](https://vuex.vuejs.org/)
	- [Nuxt Documentation](https://nuxtjs.org/examples/vuex-store)
- Axios
	- [Official Documentation](https://github.com/axios/axios)
	- [Nuxt Documentation](https://axios.nuxtjs.org/)

Note: Some references has multiple documentations, mostly another documentation for Nuxt. That is because on top of the official documentations, Nuxt adds in some shortcuts and helper functions that is unique to Nuxt.

If you are more of a visual learner, you can also visit and watch these YouTube channels:
- [Freecodecamp](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ) - has complete tutorials that span several hours and covering a lot of the topic.
- [Andre Madarang](https://www.youtube.com/channel/UCtb40EQj2inp8zuaQlLx3iQ)
- [LevelUpTuts](https://www.youtube.com/c/LevelUpTuts/featured)

**Please still read the documentation as they are more updated and explains a lot more.**
