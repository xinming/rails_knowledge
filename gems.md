## Rails/Ruby Gems Reference
#### General Gems / Must know!
* **active_admin** [Github](https://github.com/gregbell/active_admin) [Web](http://www.activeadmin.info/) [Video](http://railscasts.com/episodes/284-active-admin)   
Remarks: use the master branch on github for now to avoid issues with outdated jQuery-ui gem.   
`gem "activeadmin", github: "gregbell/active_admin"`
* **simple_form**: Form builder [Video](http://railscasts.com/episodes/234-simple-form-revised) 
* **formtastic**: Another form builder. used in activ_eadmin [Github](https://github.com/justinfrench/formtastic)
* **cocoon** Dynamic nested forms using jQuery [Github](https://github.com/nathanvda/cocoon)
* **migrant**: very useful if you are not into writing migrations by hand
 [Github](https://github.com/pascalh1011/migrant)
* **carrierwave**: file uploads [Video](http://railscasts.com/episodes/253-carrierwave-file-uploads) [Github](https://github.com/carrierwaveuploader/carrierwave) and mini_magick  [MiniMagick integration](http://carrierwave.rubyforge.org/rdoc/classes/CarrierWave/MiniMagick.html)
* **inherited_resources**: Auto rails resources. saves time writing controllers [Github](http://railscasts.com/episodes/230-inherited-resources) [Video](http://railscasts.com/episodes/230-inherited-resources)
* **has_scope:works** well with rails model scopes, generates controller parameters for scopes autoamtically [Github](https://github.com/plataformatec/has_scope)
* **kaminari**: pagination [Video](http://railscasts.com/episodes/25* 4-pagination-with-kaminari)
* **devise** [Video](http://railscasts.com/episodes/209-devise-revised) [Video W/ Omniauth](http://railscasts.com/episodes/235-devise-and-omniauth-revised)
* twitter bootstrap
  * https://github.com/seyhunak/twitter-bootstrap-rails (Use this is easiest for Bootstrap 2.3)
  * **bootstrap-sass** (Use this is easiest for Bootstrap 3)
  * **bootstrap-sass-extras** (adds generators to bootstrap-sass)
  * [Video 1](http://railscasts.com/episodes/328-twitter-bootstrap-basics) 
  * [Video 2](http://railscasts.com/episodes/329-more-on-twitter-bootstrap)
  * **font-awesome-rails**
* omniauth (See section below)
* **figaro** YAML-based Rails configiration [Github](https://github.com/laserlemon/figaro)
* 




<hr />

###### Views/Presentors
* **draper** [Github](https://github.com/drapergem/draper) [Video](http://railscasts.com/episodes/286-draper)

###### SQL and NOSQL
* **squeel** [Github](http://railscasts.com/episodes/354-squeel) [Video](http://railscasts.com/episodes/354-squeel)
* **mongoid** [Video](http://railscasts.com/episodes/238-mongoid-revised)


###### Social Networks

* Facebook Graph API [Video](http://railscasts.com/episodes/361-facebook-graph-api)
  * **koala** (facebook graph API etc.)
* Facebook Javascript API [Video](http://railscasts.com/episodes/360-facebook-authentication)
* **omni-auth**
  * [Video w/ Devise](http://railscasts.com/episodes/235-devise-and-omniauth-revised)
  * [Simple Omniauth Video](http://railscasts.com/episodes/241-simple-omniauth-revised)
  * [Part 1](http://railscasts.com/episodes/235-omniauth-part-1)
  * [Part 2](http://railscasts.com/episodes/236-omniauth-part-2)
  * [Video Facebook authentication](http://railscasts.com/episodes/360-facebook-authentication)


######API Clients and Servers:
* **rest-client**
* **grape** (for making REST API, lightweight similar to sinatra)
* **strong_parameters** (for validating request params in rails rest APIs)

######CMS:
* **refineryCMS** [Video 1](http://railscasts.com/episodes/332-refinery-cms-basics) [Video 2](http://railscasts.com/episodes/333-extending-refinery-cms)
###### Background Tasks:
* **sidekiq** [Video](http://railscasts.com/episodes/366-sidekiq)
* **resque** [Video](http://railscasts.com/episodes/271-resque)
* **delay_jobs** [Video](http://railscasts.com/episodes/366-sidekiq) [Github](https://github.com/collectiveidea/delayed_job) [Frontend Github](https://github.com/ejschmitt/delayed_job_web)


###### Others:
* **acts-as-taggable-on** [Video](http://railscasts.com/episodes/382-tagging) [link](https://github.com/mbleigh/acts-as-taggable-on)
* **stateful**
* **AASM** State Machine [Github](https://github.com/aasm/aasm)
* **brakeman** (security scan gem)
* **public_activity** Easy activity tracking for models [Github](https://github.com/pokonski/public_activity)
* **Ransack** [Github](https://github.com/NARKOZ/holder_rails)

#### Deployment &  Server Administration
* Heroku
* monitoring: monit/god
* puma, unicorn, passenger
* apache/nginx
* automated deployment: capistrano/etc..

#### Testing
* Unit::Test and Mini Test
* RSpec (peepcode video)
* Fixtures and Factories
* Factory Girl [Video](http://railscasts.com/episodes/158-factories-not-fixtures-revised)
* Guard [Video](http://railscasts.com/episodes/264-guard)