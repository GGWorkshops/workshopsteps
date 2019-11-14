## Step 1: Install XCode
- Xcode allows compilation and running of programs

` $ xcode-select --install `

## Step 2: Install zlib
- Only needed for MacOS Mojave 10.14 and above
` $ sudo installer -pkg /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg -target /`

## Step 3: Install Homebrew (2 commands)
- Homebrew helps download programs such as gradle
`$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" `
` $ brew update `

## Step 4: Install Git
` $ brew install git `

## Step 5: Set up SSH key.
` $ ssh-keygen -t rsa -b 4096 -C "your_email_used_to_create_github_account@example.com" `
- Press enter when prompted to enter the file in which to save the key.
- Press enter when says to enter a passphrase
` pbcopy ~/.ssh/id_rsa.pub `
- Copy to clipboard the ssh-rsa to the last letter of your email or machine name at the end.
- Go to Github and press New SSH Key
- Add SSH Key

### Step 6: Install Java
` $ brew tap caskroom/cask `
` $ brew cask install java `

## Step 7: Install Gradle
` $ brew install gradle `
- Check gradle version and make sure it is Gradle 5 or higher

## Step 8: Install pyenv
` $ brew install pyenv `
` $ echo -e 'eval "$(pyenv init -)"\n' >> ~/.bash_profile `

## Step 9: Install pip/ pipenv
- Restart terminal
` $ pyenv install 3.6.7 `
` $ pyenv global 3.6.7 `
` $ pip install --upgrade pip `
` $ pip install proselint `
` $ pip install pipenv `
` $ gem install mdl `
