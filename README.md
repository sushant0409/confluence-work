# confluence-work

In the createPage.sh, 
   use --user tag if we want to use useremail. need to pass user email id and API token as <username>:<api_token>

Another way is to use authorization header as used in the given script
  base64 encoded string needs to be generated after entering following command

  echo -n your_email@domain.com:your_user_api_token | base64

replace the confluence host as well the space key id.