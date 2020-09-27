 ```
    <button class="ui compact labeled icon button" style="margin-bottom:20px;" id="modal-button">
      <i class="plus icon"></i>
            New Modal
    </button>
          
          
          
      <div class="ui modal">
        <div class="scrolling content">
         Success! You just create a modal
        </div>
    
    </div>	

<script>
    $("#modal-button").click( function(){
        $(".ui.modal").modal("show");
    });

 </script>
    
```
