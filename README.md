## About This Effort

Austin “playbook” Rough Draft We’re going to have one.
An experiment space for using Jekyll with gh-pages

## Contributing
Feedback and suggestions on the site are essential and can be discussed on [GitHub Issues](https://github.com/cityofaustin/playbook/issues). You may also propose changes to the content directly by submitting a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests").

To propose a change from your browser, [select a critera document](https://github.com/cityofaustin/playbook/tree/master/_criteria "Link to the Criteria Markdown files") in the `_criteria` folder. You can use Github's editor to edit files and submit a pull request for your changes to be merged into the document.

The site introduction can also be updated in the same way and can be found [here](https://github.com/cityofaustin/playbook/blob/master/_includes/intro.md "Link to the intro Markdown File").

To propose changes to the HTML and CSS please preview the site locally before opening a pull request.

If you would like to see and discuss the changes that other people have proposed, [visit the Pull Requests section](https://github.com/cityofaustin/playbook/pulls "Link to the Pull Requests Section of Github") and [the Issues page](https://github.com/cityofaustin/playbook/issues "Link to the Issues Section of Github").

## Technical Stuff

The site is compiled from [Markdown](https://guides.github.com/features/mastering-markdown/ "Link to More Information About Markdown") files using [Jekyll](https://github.com/jekyll/jekyll "Link to More Information about Jekyll"). To propose a specific change, you can submit a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests") with your change to one of these source Markdown files. Criteria documents  are available in the `_criteria` [folder](https://github.com/cityofaustin/playbook/tree/master/_criteria "Link to the criteria Markdown files"), 

### Running the Site Locally
#### Requirements

To run the site on your own computer, you will first need to install Vagrant and Virtualbox

- VirtualBox - Free open source virtualization software [Download Virtualbox](https://www.virtualbox.org/wiki/Downloads)
- Vagrant **1.6.3+** - Free open source tool for building complete development environments with virtualbox images [Download Vagrant](https://www.vagrantup.com)
- Git - Source Control Management [Download Git](http://git-scm.com/downloads)

#### Steps

1. [Fork this repository](http://help.github.com/fork-a-repo/ "Instructions for Forking Your Repository") and clone it on your computer.

2. Open a terminal, shell, command line or whatever you like to call it and change directory to the cloned repo location on your computer.

3. Run the command `$ vagrant up`. It may take several minutes for the machine to come up the first time. 

4. Run the command `$ vagrant ssh`. You are now talking to the Ubuntu virtual machine.

5. cd into vagrant's synced directory `$ cd /vagrant/`

6. Run `$ jekyll serve --watch --force_polling`

7. Visit [http://localhost:4000/playbook](http://localhost:4000/playbook/) in your browser to preview the site and let the magic begin! You can edit the files from your local machine. They will be synced to the VM where Jekyll will rebuild the site. Refresh your browser to see the changes.

8. Don't forget to shutdown the vagrant box when your done using the commands `$ vagrant halt` or `$ vagrant destroy` 

### Editing the Styling

This project uses the open source [Foundation](http://foundation.zurb.com/ "Link to Learn More About Foundation") framework. If you would like to make changes to the site's styles, you should edit the `css/app.css` file. 
**Do not** make changes to any other css file directly.

### Editing the HTML

coming soon


## License
Um?
