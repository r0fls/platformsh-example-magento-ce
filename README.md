# platformsh-example-magento-ce
Example Platform.sh project with Magento CE

Steps to use:

1. Clone this repo

   ```
   git clone https://github.com/r0fls/platformsh-example-magento-ce.git
   cd platformsh-example-magento-ce
   ```
2. Create a [platform](https://accounts.platform.sh/platform/buy-now). Choose to import your own code when it asks you and stop there.
3. Use the code in the bottom right from step 2 to push magento to your platform, which will look like this:
  
  ```
  git remote add remote <platform-git-url>
  git push -u platform master
  ```
