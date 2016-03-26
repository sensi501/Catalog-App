Catalog Application
by: Jamal Pilgrim

Readme
    To successfully run this application you will need to: 
        
    Installation
    
    -   Install Python 2.7.10 or later from the python website below
		'https://www.python.org/downloads/release/python-2710/' 
		also select the version that matches your operating system
		
    -   Install Vagrant virtual machine from 'http://vagrantup.com/'
        
    -   Install Virtual Box from 'https://www.virtualbox.org/'
		
    -   For instructions on installing git go to 'http://www.git-scm.com/book/en/v2/Getting-Started-Installing-Git'
        
    -   Sign up to or login to github.com then, fork the repository from 'http://github.com/udacity/fullstack-nanodegree-vm'
        
    -   Clone your forked repository from github.com to your local machine using git bash or terminal or command line
        
    -   Navigate to '/vagrant/catalog' within the locally cloned repository
    
    -   Copy the files of this projects folder to '/vagrant/catalog'
    
    
    Virtual Machine startup
    
    -   Navigate to '/vagrant' and input: 'vagrant up' then 'vagrant ssh'
    
    -   Navigate to '/vagrant/catalog' 
    
    Catalog Application Database Setup
    
    -   Delete the 'catalog.db' file in vagrant/catalog if it exists
    
    -   Run 'database_setup.py' located in vagrant/catalog
    
    
    Application Startup
    
    -   Run 'application.py' to start the Catalog Application web server
    
    -   Access the web site by navigaing to 'http://localhost:8000'
    
    
    Site Hierarchy
    
        *   NOTE: replace '<item_name>' with: 
                *  An item name also separate with '_'(Underscore character) if item name has spaces

        *   NOTE: replace '<category_name>' with: 
                *  A category name
    
        -   The following web addresses are interactive web pages:
        
            -   Home Page or Initial Landing Page: 'http://localhost:8000/' and 'http://localhost:8000/catalog'
            
            -   Specific Category Items Page: 'http://localhost:8000/catalog/<category_name>'
            
            -   Item Description Page: 'http://localhost:8000/catalog/<category_name>/<item_name>'

            -   Add New Item Page: 'http://localhost:8000/catalog/new'            

            -   Update Item Page: 'http://localhost:8000/catalog/<item_name>/edit'
                
            -   Delete Item Page: 'http://localhost:8000/catalog/<item_name>/delete'
            
        -   The following web addresses are JSON API endpoints:
        
            -   List All Database Items Table Entries: 'http://localhost:8000/catalog.json'
            
            -   List All Specific Database Items Table Entries: 'http://localhost:8000/catalog/<category_name>.json' 


Revisions

    -   3/26/2016 - Line 149 prevented gdisconnect() from disconnecting due to non-existent access_token string
                    Line 149 Changed:
                        From: 'access_token = credentials.access_token'
                        To: 'access_token = credentials'

Contact
		email address:	sensi501@gmail.com