

![Screenshot 2023-07-08 190402](https://github.com/singhadity02394/Singh_Aditya/assets/136795482/f6df6bb4-f42f-4947-956a-0f64d5adf91f)

[#Sorting Visulizer Html](http://127.0.0.1:5500/sorting.html)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorting Visualizer</title>

    <link rel="stylesheet" href="style.css">

</head>
<body>

    <header>
        <nav>
            <div class="array-inputs">
                <p>Size of the array:</p>
                <input id="a_size" type="range" min=10 max=150 step=1 value=80>
                <p>Speed of the algorithm:</p>
                <input id="a_speed" type="range" min=1 max=5 step=1 value=4>
                <button id="a_generate">Generate New Array!</button>
            </div>

            <div class="header_right">
                <p class="nav-heading">Sorting visualizer</p>

                <div class="algos">
                    <button >Bubble</button>
                    <button >Selection</button>
                    <button >Insertion</button>
                    <button >Merge</button>
                    <button >Quick</button>
                    <button style="margin-right: 0px;">Heap</button>
                </div>
            </div>

        </nav>
    </header>

    <section>

        <div id="Info_Cont1">

            <h3>TIME COMPLEXITY</h3>

            <div class="Complexity_Containers" id="Time_Complexity_Types_Container">

                <div class="Pair_Definitions">
                    <p class="Sub_Heading">Worst case:</p>
                    <p id="Time_Worst"></p>
                </div>
                
                <div class="Pair_Definitions">
                    <p class="Sub_Heading">Average case:</p>
                    <p id="Time_Average"></p>
                </div>
                
                <div class="Pair_Definitions">
                    <p class="Sub_Heading">Best case:</p>
                    <p id="Time_Best"></p>
                </div>

            </div>

        </div>

        <div id="array_container">
            
        </div>

        <div id="Info_Cont2">

            <h3>SPACE COMPLEXITY</h3>

            <div class="Complexity_Containers" id="Space_Complexity_Types_Container">

                <div class="Pair_Definitions">
                    <p class="Sub_Heading">Worst case:</p>
                    <p id="Space_Worst"></p>
                </div>
                
            </div>

        </div>
        
        
</section>

    <footer>

    </footer>

    <script src="main.js"></script>   <!--This should be at the end of body and should be loaded before sorts.js-->
    <script src="visualizations.js"></script>  <!--This should be loaded after main.js-->

    <script src="bubble_sort.js"></script>
    <script src="selection.js"></script>
    <script src="insertion.js"></script>
    <script src="merge.js"></script>
    <script src="quick.js"></script>
    <script src="heap.js"></script>

    <!--Searching-->
    <div >
    
        <br />

    <nav style="height:50px;"><h1><b>Searching visualizer</b></h1></nav>
        <p class="header">Linear Search</p>
        <div id="array"></div>
        <br /><br />
        <div style="text-align: center">
        <label for="fname">
            Number to be Searched:
        </label>
        <input type="text" id="fname" name="fname" />
        <br /><br />
        <button class="bt" id="btn"
                onclick="LinearSearch()">Search
        </button>
        <br />
        <br />
        <div id="text"></div>
        
            </div>
        </div>
        <h3>TIME COMPLEXITY</h3>
        <br>
        <br>

            <div class="Complexity_Containers" id="Time_Complexity_Types_Container2">

                <div class="Pair_Definitions">
                    <p class="Sub_Heading">Worst case:</p>
                    <p id="Time_Worst2"></p>
                </div>
                
                <div class="Pair_Definitions">
                    <p class="Sub_Heading">Average case:</p>
                    <p id="Time_Average2"></p>
                </div>
                
                <div class="Pair_Definitions">
                    <p class="Sub_Heading">Best case:</p>
                    <p id="Time_Best2"></p>
                </div>
                </div>
                <br>
                <br>
                <br>

                <div id="Info_Cont2">

                    <h3 sty>SPACE COMPLEXITY</h3>
                    <br>
                    <br>
        
                    <div class="Complexity_Containers" id="Space_Complexity_Types_Container">
        
                        <div class="Pair_Definitions">
                            <p class="Sub_Heading">Worst case:</p>
                            <p id="Space_Worst2"></p>
                        </div>
                        
                    </div>
        
                </div>
        <!--binary sea-->

        <div>
            <p class="header1">Binary Search</p>
            <div id="arr"></div>
    <br /><br />
 
    <div style="text-align: center">
      <label for="fname2">
        Number to be Searched:
      </label>
      <input type="text1" id="fname2"
             name="fname2" />
      <br /><br />
      <button  class="bt" id="btn1"
              onclick="BinarySearch()">Search</button>
      <br />
      <br />
      <div id="text1"></div>
    </div>
   
 
 
 
        </div>
    

        <script src="Searching.js"></script>
        <script src="Binary.js"></script>
   
       
      
</body>
</html>
```html