1. Clone this repository  
```
git clone git@github.com:etorovsky/rails_init.git <Your_app_name>
cd <Your_app_name>
```

2. Install Rails
```
bundle install --path ./vendor/bundle
```

3. Create Rails app with options.  
```
bundle exec rails new . `./script/rails_new_options`
```  
You will be asked: `Overwrite /path/to/your/Gemfile? (enter "h" for help) [Ynaqdh]` then type "Y".


4. Install gems using your Rails app.
```
bundle install
```
