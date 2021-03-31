https://www.codeply.com/p/6Aceq9NulN
# BootStrap Grid

## Unresponsive Grid
    <div class="row">
        <div class="col" style="background-color:red; border: 1px solid;">
            col
        </div>

        <div class="col" style="background-color:red; border: 1px solid;">
            col
        </div>
    </div> 


    <div class="row">
        <div class="col-6" style="background-color:green; border 1px solid">
            col-6
        </div>

        <div class="col-3" style="background-color:pink; border 1px solid">
            col-3
        </div>

        <div class="col-2" style="background-color:Tomato; border 1px solid">
            col-3
        </div>

        <div class="col-1" style="background-color:Orange; border 1px solid">
            col-3
        </div>
    </div>
    
- Problem with this is that it is not responsive.
- The columns should reduce as the screen size reduces.
    - Desktop --> Tablet --> Phone



## Responsive Grid
    <div class="row">
        <div class="col-lg-3 col-md-4 col-sm-6" style="background-color:SlateBlue; border 1px solid">
            col-lg-3 col-md-4 col-sm-6
        </div>

        <div class="col-lg-3 col-md-4 col-sm-6" style="background-color:Khaki; border 1px solid">
            col-lg-3 col-md-4 col-sm-6
        </div>

        <div class="col-lg-3 col-md-4 col-sm-6" style="background-color:LightSkyBlue; border 1px solid">
            col-lg-3 col-md-4 col-sm-6
        </div>

        <div class="col-lg-3 col-md-4 col-sm-6" style="background-color:Tan; border 1px solid">
            col-lg-3 col-md-4 col-sm-6
        </div>

    </div>
    
- col-lg-3 desktop will have 4 columns
- col-md-4 tablet will have 3 columns
- col-sm-6 phone will have 2 columns
