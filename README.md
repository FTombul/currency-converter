currency-converter
==================

currency converter helps you to calculate

Use this code to calculate the currency for example from Euro to Dollar

<form action="#">
    <p>
        Euro-Betrag<br/>
        <input type="text" id="euro"
               onfocus="leereFeld('euro');" onkeyup="euroZuDollar();" />
    </p>
    <p>
        Dollar-Betrag<br/>
        <input type="text" id="dollar"
               onfocus="leereFeld('dollar');" onkeyup="dollarZuEuro();" />
    </p>
	
	<p>
        <input type="text" id="betragInEuro" onkeyup="euroZuDollar();" />
    </p>
</form>


