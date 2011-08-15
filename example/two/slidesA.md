!SLIDE subsection

# Subsection Slide #

!SLIDE

# Code Slide #

	@@@ ruby
	require 'sinatra/base'

	class MyApp < Sinatra::Base
	  set :sessions, true
	  set :foo, 'bar'

	  get '/' do
	    'Hello world!'
	  end
	end	

!SLIDE execute

# Executable JavaScript #

	@@@ javascript
	result = 3 + 3;

!SLIDE execute

# Executable Ruby #

 	@@@groovy
       result = [1,2].collect{it*2}
       println result


!SLIDE

# Write your own slides #

## Using [markdown](http://daringfireball.net/projects/markdown/)

    !SLIDE
    
    # Title of the slide #
    
    How easy is this?
