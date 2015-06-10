testProject3  -- ANGULAR

need node and bower install

check by doing:
  node -v
  bower -v

then run:
  bower init

install packages:
  bower install jquery --save
  bower install bootstrap --save
  bower install angular --save
  bower install angular-resource --save

  The --save will add the package into your bower.json file as dependencies.
  Then when you clone your repo again you can do a bower install in exactly the
  same way as you bundle install with Ruby

  Now we don't really want to add bower_components into our repository -
  most people consider it bad practice.
  Because we don't want to commit those dependencies we need to add bower_components
  to our .gitignore file
