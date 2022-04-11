
Refer to this repository to apply for free crust storage specifically for developers and this hackathon. [Github Repo](https://github.com/crustio/free-storage)

Video demo: [link](https://drive.google.com/file/d/1QqfHWOrBblI-qYQEgO1GR4KOrTCRZb7d/view?usp=sharing)

# Steps to run the CRUST App

1. Fork the repository<br>
2. Install go-ipfs from https://dist.ipfs.io/#go-ipfs<br>
3. Extract the downloaded files and add the go-ipfs directory PATH to system environment varibles<br>
4. Open a terminal window and execute<br>
```ipfs init```<br>
5. Open another terminal and execute the following to start the daemon server<br>
```ipfs daemon```<br>
6. Once the daemon server is up and running go to the local project directory and install the dependencies using the following code<br>
```npm i```<br>
7. Now run index.js<br>
```node index.js```<br>
Note: In case there's a dependency error regarding node-fetch package, ececute the following<br>
```npm i node-fetch@2```<br>
8. Go to localhost:3000 on a browser to view the build.
9. Upload a file by providing a file name and submit the form.
10. The submission will make a POST request to the IPFS server and return a cid on the screen.

# Steps to setup the CRUST Wallet
1. Install the CRUST wallet extension from https://chrome.google.com/webstore/detail/crust-wallet/jccapkebeeiajkkdemacblkjhhhboiek?hl=en
2. Create an account as guided by the extension.
3. Save your seed in a text file.

# Steps for storing a file on the CRUST network
1. Replace the *fileCid* variable in *crust.js* file with the cid generated through ipfs.
2. Also replace the seed value named as *krp* in *crust.js* file with your seed you saved during CRUST wallet installation.
3. Now run the file using<br>
```node crust.js```<br>

# Notion Link for reference
[Link](https://amanv2k.notion.site/amanv2k/hacKnight-e6db104a46cf40c8a87488433d753414)

# Resources
1. https://wiki.crust.network/docs/en/build101
2. https://www.youtube.com/watch?v=1Ud4HJNak4M&t=425s&ab_channel=zapppelphilippp
