<!DOCTYPE html>
<html>

<body style="justify-content: center;background-color: antiquewhite;">




    <div class="container-fluid" style="border: 2px solid black;">
        <form>
            <label><b>CGPA CALCULATOR</b></label><br>
            <label>PS grade:</label><br>
            <input type="text" id="t1"> <br>
            <label>PC grade:</label><br>
            <input type="text" id="t2"><br>
            <label for="lname">WT grade:</label><br>
            <input type="text" id="t3"><br>
            <label for="lname">DBMS grade:</label><br>
            <input type="text" id="t4"><br>
            <label for="lname">DAA grade:</label><br>
            <input type="text" id="t5"><br><br><br>

        </form>
    
    <button onclick="myFunction()">SUBMIT</button>
    <p id="demo"></p>

</div>
    <script>
        function myFunction() {
            var a = document.getElementById("t1");
            var b = document.getElementById("t2");
            var c = document.getElementById("t3");
            var d = document.getElementById("t4");
            var e = document.getElementById("t5");
            var sum = (parseInt(a.value) + parseInt(b.value) + parseInt(c.value) + parseInt(d.value) + parseInt(e.value)) / 5;
            if (sum != null) {
                document.getElementById("demo").innerHTML = "The cgpa is: " + sum;
            }
        }
    </script>

</body>

</html>
