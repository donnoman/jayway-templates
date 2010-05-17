## Jayway Rails Template
This file contains Rails templates that we use at Jayway. 

It is used to create a new project with Jayway specific defaults. It creates the Rails structure, sets up a RVM Gemset, runs "bundle install", runs the generators and then checks it all into a new Git repository.

### Usage

    rails NAME -m http://github.com/andersjanmyr/rails_templates/raw/master/jayway_rails_template.rb


### Requirements
* RVM must be installed since it uses RVM Gemset.
* Rails --pre must be installed since everything depends on it.


### Defaults
#### Test
* rpec and rspec-rails, replaces test_unit
* factory_girl replaces yaml-fixtures
* cucumber is installed for integration testing

#### View
* HAML replaces ERB
* Formtastic for forms
* SASS, with the new dialect SCCS replaces CSS
* Compass, with Blueprint is used to get prepared CSS mixins and variables
* jQuery and jQuery UI, replaces PrototypJS



