A robust slugging gem that replaces non-alphanumeric characters with a dash and removes multiple, consecutive instances of a dash when generating a slug.

Install the gem by adding the following to your Gemfile:
gem 'sluggable_gemille'

Then run bundle install.

After installing the gem, require 'sluggable_gemille' in application.rb.

For the models to which you'd like to add this functionality, include SluggableGemille and specify your sluggable_column (Ex.: sluggable_column :title).
