
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="robots" content="noindex">

    <title>Accordion Fancy Animation - Bootsnipp.com</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
     <link href="css/collapse.css" rel="stylesheet" >
   
    <script src="//code.jquery.com/jquery-1.10.2.min.js"></script>
    <script src="//maxcdn.bootstrapcdn.com/bootstrap/3.3.0/js/bootstrap.min.js"></script>
    <script type="text/javascript">
        window.alert = function(){};
        var defaultCSS = document.getElementById('bootstrap-css');
        function changeCSS(css){
            if(css) $('head > link').filter(':first').replaceWith('<link rel="stylesheet" href="'+ css +'" type="text/css" />'); 
            else $('head > link').filter(':first').replaceWith(defaultCSS); 
        }
        $( document ).ready(function() {
          var iframe_height = parseInt($('html').height()); 
          window.parent.postMessage( iframe_height, 'http://bootsnipp.com');
        });
    </script>
</head>
<body>
	<div class="container">
    <div class="row">
        <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
            <div class="panel panel-custom">
                <div class="panel-heading" role="tab" id="headingOne">
                    <h4 class="panel-title"><table>
<tr><th>JobType</th><th>EnvId</th><th>Active</th><th>Completed</th><th>Errors</th><th>Terminated</th><th>Paused</th></tr>
<tr><td><a data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="true" aria-controls="collapseOne"><i class="glyphicon glyphicon-plus"></i></a>
 WSO</td><td>ALL</td><td>2</td><td>1</td><td>0</td><td>0</td><td>0</td></tr>
</table></h4>
                </div>
                <div id="collapseOne" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne">
                    <div class="panel-body animated zoomOut">
                        <table>
                        <tr>
                        <td></td><td><a href="#">PRD1</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td> 
                        </tr>
                        <tr>
                        <td></td><td><a href="#">PRD2</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>
                                    <tr>
                                     <td></td><td><a href="#">PRD3</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>
                          <tr>
                          <td></td><td><a href="#">PRD18</a></td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td>
                                    </tr>
                                    <tr>
                                    <td></td><td><a href="#">PRD20</a></td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>          
                          
                        </table>
                        </div>
                </div>
            </div>
         
            <div class="panel panel-custom">
                <div class="panel-heading" role="tab" id="headingTwo">
                    <h4 class="panel-title"><table>
                    <tr><td>
                        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                            <i class="glyphicon glyphicon-plus"></i> </a>
                            PBD</td><td>ALL</td><td>0</td><td>1</td><td>0</td><td>0</td><td>0</td></tr>
</table></h4>
                       
                 
                </div>
                <div id="collapseTwo" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
                    <div class="panel-body animated zoomOut">
                       <table>
                        <tr>
                        <td></td><td><a href="#">PRD1</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td> 
                        </tr>
                        <tr>
                        <td></td><td><a href="#">PRD2</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>
                                    <tr>
                                     <td></td><td><a href="#">PRD3</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>
                          <tr>
                          <td></td><td><a href="#">PRD18</a></td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td>
                                    </tr>
                                    <tr>
                                    <td></td><td><a href="#">PRD20</a></td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>          
                          
                        </table>
                       
                       </div>
                </div>
            </div>
            <div class="panel panel-custom">
                <div class="panel-heading" role="tab" id="headingThree">
                    <h4 class="panel-title">
                    <table>
                    <tr><td>
                                     
                        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseThree" aria-expanded="false" aria-controls="collapseThree">                            
                            <i class="glyphicon glyphicon-plus"></i>      </a> 
                           QPR</td><td>ALL</td><td>1</td><td>0</td><td>1</td><td>0</td><td>0</td></tr>
</table></h4>
                </div>
                <div id="collapseThree" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
                    <div class="panel-body animated zoomOut">
                        <table>
                        <tr>
                        <td></td><td><a href="#">PRD1</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td> 
                        </tr>
                        <tr>
                        <td></td><td><a href="#">PRD2</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>
                                    <tr>
                                     <td></td><td><a href="#">PRD3</a></td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>
                          <tr>
                          <td></td><td><a href="#">PRD18</a></td><td>0</td><td>0</td><td>1</td><td>0</td><td>0</td>
                                    </tr>
                                    <tr>
                                    <td></td><td><a href="#">PRD20</a></td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td>
                                    </tr>          
                          
                        </table></div>
                </div>
            </div>
        </div>
    </div>
</div>
	<script type="text/javascript">
	$(function() {

    function toggleChevron(e) {
        $(e.target)
                .prev('.panel-heading')
                .find("i")
                .toggleClass('rotate-icon');
        $('.panel-body.animated').toggleClass('zoomIn zoomOut');
    }
    
    $('#accordion').on('hide.bs.collapse', toggleChevron);
    $('#accordion').on('show.bs.collapse', toggleChevron);
})


	</script>
</body>
</html>
