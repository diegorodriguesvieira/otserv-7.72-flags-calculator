## Running

####  Install dependencies
First install Ruby on your system to get gem package manager: [see here](https://www.ruby-lang.org/en/documentation/installation/)

If you use Mac OS X install build essential packages:
```
sudo xcode-select --install
```
Now install Jekyll:
```
sudo gem install ffi -v '1.9.14'
sudo gem install bundler
sudo gem install jekyll
sudo gem install jekyll-coffeescript
```

#### Clone project and install packages
```
sudo git clone https://github.com/diegorodriguesvieira/flags-calculator.git
cd flags-calculator
bundle install
```

### Set the project to run locally
* Open _config.yml

Comment this line:
```
# baseurl: "/flags-calculator" # production
```
Uncomment this line:
```
baseurl: "" # localhost
```

#### Finally run it ;)
```
bundle exec jekyll serve
```
Then visit the URL: http://127.0.0.1:4000

Enjoy :thumbsup:

Thanks [@ranisalt](https://github.com/ranisalt) for this project! :heart:
