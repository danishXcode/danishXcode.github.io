<!doctype html>

<html lang="en">
<head>
    <script
  src="https://code.jquery.com/jquery-3.6.0.min.js"
  integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4="
  crossorigin="anonymous"></script>
   

    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="Refresh" content="120"> 
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>


    <script>


$( document ).ready(function() {
    console.log( "ready!" );

    const ids = ["0xF3956B17a7F7192Fe5F633602B15468fF3cB239d",
                 "0xc52fDeecFE2C93A8402A7f939672F3dcB2E1bAE7",
                "0xC8AB708EF0C2034995c7052363A056BeB67F6aD0",
                "0x6608bFaC5ED0364056239CF6e0B26E478B6B6Cb1"
                ] 
    const names =["Common","Amit","Haider","Prashant"]
    let baseURl = "https://api.ethermine.org/miner"
    let cnt = 0; 
    ids.forEach(id => {

    let url = baseURl +"/"+id+"/"+"currentStats";

    $.get(url, function(response){
        console.log("data -= >")
            console.log(response.data)
            let mi= response.data;
            let unpaid = parseFloat(mi.unpaid)/1000000000000000000;
            let price = parseFloat(mi.usdPerMin)*60*24*73;
            price=price.toFixed(5);
            $('#tbody').append(`<tr>
             <td>`+ names[cnt]+`</td>
            <td>`+ ids[cnt++]+`</td>
            <td>`+ unpaid+`</td>
            <td>`+ parseInt(mi.activeWorkers)+`</td>
            <td>`+  price +`</td>
           </tr>`);
    });

 });
});
    </script>
</head>

<body>
    <div class="container">
    <table  class="table" id="tableN">
        <thead>
          <tr>
            
            <th>Owner Name </th>
            <th>Farm ID</th>
            <th>Balance</th>
            <th>Active Worker</th>
            <th>Estimated/Day &#x20a8; </th>
          </tr>
        </thead>
        <tbody id="tbody">
        </tbody>
      </table>
    </div>
</body>
</html>
