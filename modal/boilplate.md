 ```
<div class="ui modal">
        <div class="scrolling content">
         <?php include_once "yoursidebar.php" ?>
        </div>
    
    </div>	
    $("#modalButton").click( function(){
        $(".ui.customModal.modal").modal("show");
    });

    <div class="ui modal">
        <div class="scrolling content">
         <?php include_once "yoursidebar.php" ?>
        </div>
    
    </div>

    $("#modalButton").click( function(){
        
        $(".ui.customModal.modal")
            .modal({
                width: 400,
                height: 200
                })
            .modal("show");
    });
	```
