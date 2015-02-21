A robust slugging gem that replaces non-alphanumeric characters with a dash and removes multiple, consecutive instances of a dash when generating a slug.

After installing the gem, require 'sluggable_gemille'

For the models to which you'd like to add this functionality, include SluggableGemille and specify your sluggable_column (Ex.: sluggable_column title).