# GITPOD

## CONTENTS

 - What is GitPod?
 - Why GitPod?
 - Advantages & Dis-advantages of GitPod.
 - How Gitpod Works?
 - What is a Workspaces?
 - Running  project on Gitpod
 - The terminal
   -  What is the terminal or Gitpod line?
 - Source Platform
 # Overall look for GitPod is
  <img width="628" alt="gitpod" src="https://user-images.githubusercontent.com/128490912/235722550-836a3401-14eb-4b2b-96a4-44e414639b9d.PNG">


 ## _What is GitPod_ ##

   - `Gitpod is a cloud-based integrated development environment (IDE)` that allows developers to easily create and manage code in a browser-based environment. 
   - It offers a full development environment with tools, libraries, and dependencies and enables real-time collaboration and teamwork between developers. Gitpod is a Git-based platform that uses Docker to provide private development environments.

  - Since it enables them to collaborate in a single environment without the need for local installations or challenging setup procedures, `Gitpod is a popular choice for teams that work remotely or have multiple developers working on the same project`. 
  - Additionally, Gitpod is a flexible tool for a variety of development tasks because it supports a `wide range of programming languages and frameworks`.

## _Why GitPod_

  - There are several reasons why developers choose Gitpod:
    - Simple Setup:
        -  `Gitpod does not require the installation or configuration of development environments locally`. Developers don't have to download, set up, or install any software in order to establish and run a fully working IDE with Gitpod.

     - Consistency:
          - `Gitpod promotes consistency between various developer environments`. Each developer works in the same environment thanks to Gitpod, which produces a fresh workspace from a `predetermined set of instructions, lowering the risk of setup problems and faults brought on by multiple settings`.
     

     - Collaboration: 
          - `Gitpod makes it easier for developers to work together by offering a cloud-based IDE that can be used from any device with an internet connection`. This eliminates the requirement for local development environments by enabling team members to collaborate
     - Scalability:
         -  `Gitpod is highly scalable and can handle large development teams and projects with ease`. It allows multiple developers to work on the same project without performance issues or resource limitations.

      - Cost-Effective:
         -  `Gitpod eliminates the need for expensive hardware and local software installations, reducing the cost of development`. Additionally, Gitpod offers flexible pricing plans that enable developers to pay only for what they need.

Overall, Gitpod provides an efficient and streamlined development experience that allows developers to focus on writing code rather than dealing with infrastructure issues.

## _ Advantages & Dis-advantages of GitPod_

###  _`Advantages`_
Gitpod is a 

  Gitpod is a cloud-based development environment that eliminates the need for developers to set up local development environments manually. 
  - It provides
  1. consistent development environments, 
  2. cloud-based development, 
  3. workspace snapshots, 
  4. automatic environment setup, 
  5. integration with version control, 
  6. collaboration features,
  7.  extensibility, 
  8. A  wide range of extensions and integrations with popular tools and services.
  
 Gitpod provides a streamlined and `efficient development experience, ensuring consistent environments, easy collaboration, and seamless integration with version control systems`.
 
  It simplifies the setup process, reduces onboarding time, and enhances productivity for individual developers and teams.
 

  ### _`Dis-Advantages`_

  Gitpod is a cloud-based IDE that offers several advantages, but there are also potential disadvantages to consider.
  -  These include internet dependence,
  - limited access to local resources,
  - security concerns, subscription fees, 
  - learning curve.
  - Gitpod is cloud-based, `so it does not have direct access to local resources such as external devices, local databases, and custom tools`.

  - `Security concerns include data privacy and security, subscription fees, and a learning curve`. 
  
  Overall, Gitpod offers many advantages, but developers should also consider the potential disadvantages before deciding whether it's the right development environment for their needs.

## How Gitpod Works?
   Gitpod is a cloud-based integrated development environment (IDE) that allows developers to
   1. write,
   2. review, and 
   3. collaborate on code without the need for local setup or installation.
   
  -  It provides a fully `functional development environment in the browser`, which is `pre-configured and ready to use`. 
 
  -  It also provides a web-based IDE that includes features such as
  1. code editing, 
  2. syntax highlighting, 
  3. terminal, 
  4. file explorer, and 
  5. integration with version control systems like Git.
  
  -  It also supports 
     - `collaborative development by allowing multiple developers` to work together in the same workspace. 
     - Pricing is available with different pricing plans, allowing developers to focus more on coding and collaboration.


## What is a Workspaces?

  GitPod uses a `workspace concept to allow you to have multiple environments for your projects`. Each project that you open will be `opened inside its own isolated environment, which means that any changes made within one project are not reflected on the other ones and vice versa`.
  -  This makes it easy to switch between different branches or commits without worrying about breaking anything.`


A case for working with multiple repositories at a time
A typical architecture these days is server-side rendering (SSR). You generate the view by calling backend services on the frontend server instead of calling your API from client devices. If you develop on your local machine, two repositories will be open in two IDE windows. Every service can communicate with each other as they are all running on the same machine.

![locahost-ssr](https://github.com/GaneshPelluru/Begineers/assets/128490912/55787227-55ba-4f5b-ba30-db0735e9e570)


Multiple services can communincate with each-other when running on the same machine
Local setup
In Gitpod, each workspace runs in a secure sandbox. You can expose ports so that only your browser can access them. However, the workspaces cannot communicate with one another.

In Gitpod each workspace runs in a secure sandbox, workspaces cannont communicate with one another![gitpod-workspace-without-tailscale](https://github.com/GaneshPelluru/Begineers/assets/128490912/3cc5ffde-988d-405f-93b3-d9024e3bec16)

Gitpod workspaces are secure and isolated
As long as only the browser interacts with the API, this will work with Gitpod without any changes. If you develop single-page applications and static sites where every network request is a client-side fetch, you don’t need Tailscale.

But if your application has a server-side that needs to fetch data from another workspace, it becomes a networking problem. The application server requires a secure network tunnel between them to send a request outside of its workspace and into the API workspace.

This is what Tailscale is made for ✨![gitpod-workspaces-with-tailscale](https://github.com/GaneshPelluru/Begineers/assets/128490912/2e339af7-3a5b-4d50-b383-0c4ad7759db8)


Connect multiple workspaces on Gitpod using Tailscale
Establish secure tunnel using Tailscale
Connecting multiple workspaces together with Tailscale
We can run Tailscale in each of our Gitpod workspaces, which will make them part of your “tailnet”, a secure VPN consisting of your machines that can access each other. Traffic over your “tailnet” is fully end-to-end encrypted, with each workspace having its private key, so anyone, not even Tailscale, is capable of reading the traffic.

In Gitpod, each workspace can log into Tailscale and receive a list of secure IP addresses of other workspaces connected to your “tailnet”. It is only possible to connect to these IPs from machines running Tailscale, which can be your workspaces or your local machines.

Tailscale comes pre-installed with gitpod/workspace-full, Gitpod’s base image for workspaces. So if you are using the default image or a custom docker image based on workspace-full, you are ready to go 🚀; else, you will need to add instructions to install Tailscale into your workspace.
