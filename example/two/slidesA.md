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

!SLIDE

    @@@ erlang
        Output = process(Input, []).

        process([First|Rest], Output) ->
            NewFirst = do_stuff(First),
            process(Rest, [NewFirst|Output]);

        process([], Output) ->
            lists:reverse(Output).

!SLIDE execute

# Executable JavaScript #

	@@@ javascript
	result = 3 + 3;

!SLIDE execute

# Executable Groovy #

	@@@groovy
	result = (0..4).collect{[it*2, 2**it]}.transpose()
	println result

!SLIDE execute
# Executable Coffeescript #

    @@@coffeescript
    add = (a, b) ->
      "#{a}+#{b} is #{a+b}"

    result = add 2, 3


!SLIDE

# Write your own slides #

## Using [markdown](http://daringfireball.net/projects/markdown/)

    !SLIDE
    
    # Title of the slide #
    
    How easy is this?
