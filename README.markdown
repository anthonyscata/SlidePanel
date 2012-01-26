#Quickstart

##Include required files

    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
    <script type="text/javascript" src="js/jquery.codebomber.panel.js"></script>
    <link rel="stylesheet" type="text/css" href="css/jquery.codebomber.panel.css">

#Add a panel element to your html

    <div id="panel" class="cb_slide_panel">
        <div class="wrapper">
          <a class="close" href="#">Close</a>
          <div class="inner">
            <div class="wrapper"></div>
          </div>
        </div>
    </div>

##Load the plugin on your element 
    <script type="text/javascript">
        $(document).ready(
            function(){
                $('#panel').codebomber_Panel();
            }
        );
    </script>
    
    
##Add a panel trigger
The href attribute is used to load external HTML content into your panel
    
    <a href="external.php" rel="panel" id="show">Show Panel</a>
    


##Misc

If you pass an element to the plugin that does not currently existin the dom, the plugin will create a default element with the above format.