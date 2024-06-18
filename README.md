[![Banner](https://github.com/clouddrove/terraform-gcp-vpc/blob/master/docs/CloudDrove.png)][website]
<h1 align="center">
    DevOpsBox


</h1>

<p align="center" style="font-size: 1.2rem;">
    DevOpsBox repo is designed to make devops machine setup easy with Ansible role.
</p>


<p align="center">

<a href="https://www.ansible.com">
  <img src="https://img.shields.io/badge/Ansible-2.13-green?style=flat&logo=ansible" alt="Ansible">
</a>
<a href="https://github.com/clouddrove/DevOpsBox/releases/latest">
  <img src="https://img.shields.io/github/release/clouddrove/DevOpsBox.svg" alt="Latest Release">
</a>
<a href="LICENSE.md">
  <img src="https://img.shields.io/badge/License-APACHE-blue.svg" alt="Licence">
</a>
<a href="https://ubuntu.com/">
  <img src="https://img.shields.io/badge/ubuntu-22.x-orange?style=flat&logo=ubuntu" alt="Distribution">
</a>
<a href="CHANGELOG.md">
  <img src="https://img.shields.io/badge/Changelog-blue" alt="Changelog">
</a>


</p>
<p align="center">

<a href='https://facebook.com/sharer/sharer.php?u=https://github.com/clouddrove/DevOpsBox'>
  <img title="Share on Facebook" src="https://user-images.githubusercontent.com/50652676/62817743-4f64cb80-bb59-11e9-90c7-b057252ded50.png" />
</a>
<a href='https://www.instagram.com/cloud_drove?igsh=cHJqaDY3bGtnYmh3' title="Follow On Instagram">
  <img src="https://github.com/gauravghongde/social-icons/blob/master/SVG/Color/Instagram.svg" width="23" height="23" />
</a>
<a href='https://www.linkedin.com/shareArticle?mini=true&title=DevOpsBox&url=https://github.com/clouddrove/DevOpsBox'>
  <img title="Share on LinkedIn" src="https://user-images.githubusercontent.com/50652676/62817742-4e339e80-bb59-11e9-87b9-a1f68cae1049.png" />
</a>
<a href='https://twitter.com/intent/tweet/?text=DevOpsBox&url=https://github.com/clouddrove/DevOpsBox'>
  <img title="Share on Twitter" src="https://user-images.githubusercontent.com/50652676/62817740-4c69db00-bb59-11e9-8a79-3580fbbf6d5c.png" />
</a>

</p>
<hr>


Prepared by Clouddrove, this Ansible role is meticulously designed to facilitate the seamless setup of your machine with a suite of essential DevOps tools. 🚀

The playbook is primed for execution on the local host, ensuring a swift and hassle-free environment setup. 💻
    
Currently, it is optimized for Ubuntu-based Linux distributions. 🐧

## Prerequisites

This module has a few dependencies: 

- [Ansible2.13](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- [Python](https://www.python.org/downloads)
  
## Getting Started 🌟

To utilize this playbook:

1. Clone this repository to your local machine.
2. Navigate to `inventories/vars.yml` and update the variables to match your configuration:

    ```yaml
    git_user: "your_username"
    git_email: "your_email@example.com"
    ssh_user: "your_username"
    ```

3. Execute the playbook from the terminal with the following command:

    ```bash
    ansible-playbook -i ./inventories/hosts.ini ./playbook/tools_setup.yml --ask-become-pass
    ```

## Included Tools 🧰

The playbook automates the installation of the following tools:

| DevOps Tools       | Description                                                  |
|--------------------|--------------------------------------------------------------|
| Git                | Version control system 📝                                    |
| Docker             | Container platform 🐳                                        |
| Docker-compose     | Tool for defining and running multi-container Docker apps 📦 |
| AWS CLI            | Command-line interface for Amazon Web Services ☁️            |
| Terraform          | Infrastructure as code software tool 🏗️                      |
| Kubectl            | Command-line tool for Kubernetes ⚙️                           |
| Helm               | Package manager for Kubernetes 📦                             |
| VS Code            | Source-code editor 💻                                        |
| Chrome             | Web browser 🌐                                               |
| Brave              | Privacy-focused web browser 🛡️                               |
| Tor                | Browser for anonymous web browsing 🕵️‍♂️                     |
| Telegram           | Messaging app 📱                                             |
| Zoom               | Video conferencing tool 📹                                   |
| Slack              | Collaboration hub for work 💬                                |
| Minikube           | Tool to run Kubernetes locally 🚜                            |
| Lens               | Kubernetes IDE 🔍                                             |
| SSH Keys           | Secure shell keys for authentication 🔑                       |
| Oh My Zsh          | Interactive shell tool for managing Zsh configuration 🖥️     |


## Prerequisite Packages 📦

In addition to the tools, the playbook installs the following prerequisite packages:

| Prerequisite Packages         | Purpose                                          |
|-------------------------------|--------------------------------------------------|
| ca-certificates               | Common CA certificates 🔒                        |
| apt-transport-https            | Transport for APT over HTTPS 🔐                  |
| lsb-release                   | Provides information about the Linux distribution📦|
| gnupg                         | GNU Privacy Guard for encryption 🔐              |
| bash-completion               | Programmable completion for Bash 🖥️              |
| gnupg2                        | GNU Privacy Guard version 2 🔐                   |
| curl                          | Tool for transferring data with URLs 🌐          |
| software-properties-common    | Manage the repositories that you install software from 🛠️ |
| virtualenv                    | Tool to create isolated Python environments 🐍   |
| python3-setuptools            | Easily build and distribute Python packages 📦   |
| unzip                         | Unpacks ZIP files 📂                             |
| libxtst6                      | Library for the X11 Testing -- Resource extension🖥️|
| libx11-xcb1                   | X11 client-side library 🖥️                       |
| libxcb-dri3-0                 | X11 Direct Rendering Infrastructure 🖥️          |
| libasound2                    | Shared library for ALSA applications 🔊          |
| libssl-dev                    | Development files for SSL libraries 🔐           |
| htop                          | Interactive process viewer 📊                     |
| openssh-server                | Secure shell server for secure access from remote machines 🔐 |

## 📑 Changelog

Refer [here](CHANGELOG.md).


## ✨ Contributors

Big thanks to our contributors for elevating our project with their dedication and expertise! But, we do not wish to stop there, would like to invite contributions from the community in improving these projects and making them more versatile for better reach. Remember, every bit of contribution is immensely valuable, as, together, we are moving in only 1 direction, i.e. forward. 

<a href="https://github.com/clouddrove/DevOpsBox/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=clouddrove/DevOpsBox&max" />
</a>
<br>
<br>

 If you're considering contributing to our project, here are a few quick guidelines that we have been following (Got a suggestion? We are all ears!):

- **Fork the Repository:** Create a new branch for your feature or bug fix.
- **Coding Standards:** You know the drill.
- **Clear Commit Messages:** Write clear and concise commit messages to facilitate understanding.
- **Thorough Testing:** Test your changes thoroughly before submitting a pull request.
- **Documentation Updates:** Include relevant documentation updates if your changes impact it.













## Feedback 
Spot a bug or have thoughts to share with us? Let's squash it together! Log it in our [issue tracker](https://github.com/clouddrove/DevOpsBox/issues), feel free to drop us an email at [hello@clouddrove.com](mailto:hello@clouddrove.com).

Show some love with a ★ on [our GitHub](https://github.com/clouddrove/DevOpsBox)!  if our work has brightened your day! – your feedback fuels our journey!


## :rocket: Our Accomplishment

We have [*100+ Terraform modules*][terraform_modules] 🙌. You could consider them finished, but, with enthusiasts like yourself, we are able to ever improve them, so we call our status - improvement in progress.

- [Terraform Module Registry:](https://registry.terraform.io/namespaces/clouddrove) Discover our Terraform modules here.

- [Terraform Modules for AWS/Azure Modules:](https://github.com/clouddrove/toc) Explore our comprehensive Table of Contents for easy navigation through our documentation for modules pertaining to AWS, Azure & GCP. 

- [Terraform Modules for Digital Ocean:](https://github.com/terraform-do-modules/toc) Check out our specialized Terraform modules for Digital Ocean.




## Join Our Slack Community

Join our vibrant open-source slack community and embark on an ever-evolving journey with CloudDrove; helping you in moving upwards in your career path.
Join our vibrant Open Source Slack Community and embark on a learning journey with CloudDrove. Grow with us in the world of DevOps and set your career on a path of consistency.

🌐💬What you'll get after joining this Slack community:

- 🚀 Encouragement to upgrade your best version.
- 🌈 Learning companionship with our DevOps squad.
- 🌱 Relentless growth with daily updates on new advancements in technologies.

Join our tech elites [Join Now][slack] 🚀


## Explore Our Blogs

 Click [here][blog] :books: :star2:

## Tap into our capabilities
We provide a platform for organizations to engage with experienced top-tier DevOps & Cloud services. Tap into our pool of certified engineers and architects to elevate your DevOps and Cloud Solutions. 

At [CloudDrove][website], has extensive experience in designing, building & migrating environments, securing, consulting, monitoring, optimizing, automating, and maintaining complex and large modern systems. With remarkable client footprints in American & European corridors, our certified architects & engineers are ready to serve you as per your requirements & schedule. Write to us at [business@clouddrove.com](mailto:business@clouddrove.com).

<p align="center">We are <b> The Cloud Experts!</b></p>
<hr />
<p align="center">We ❤️  <a href="https://github.com/clouddrove">Open Source</a> and you can check out <a href="https://registry.terraform.io/namespaces/clouddrove">our other modules</a> to get help with your new Cloud ideas.</p>

  [website]: https://clouddrove.com
  [blog]: https://blog.clouddrove.com
  [slack]: https://www.launchpass.com/devops-talks
  [github]: https://github.com/clouddrove
  [linkedin]: https://cpco.io/linkedin
  [twitter]: https://twitter.com/clouddrove/
  [email]: https://clouddrove.com/contact-us.html
  [terraform_modules]: https://github.com/clouddrove?utf8=%E2%9C%93&q=terraform-&type=&language=
