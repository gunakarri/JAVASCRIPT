# JAVASCRIPT
<html>
<head>
	<title>conditional</title>
</head>
<body>
	<script>
		var age = 22;
		var result = (age >= 18) ? 'you are eligible to vote' : 'you are not elible to vote';
		document.write(result);
	</script>
	<br>
	<script>
		var num = 9
		var ans = (num%2) ? 'prime' : 'not prime';
		document.write(ans);
	</script>
	<div id="output">conditional operator</div>

	<script>
		var output = document.getElementById('output');
		var login = false;
		var outputHolder;
		var userkey = login == true ? outputHolder = 'true' : outputHolder = 'false';
		output.innerHTML = userkey;
	</script>

	<div id="ages">Elections</div>
	<script type="text/javascript">
		var ages = document.getElementById('ages');
		var voters = 17;
		var people;
		var voterid = voters>=18 ? people = 'eligible for vote' : people = 'not elible for vote'
		ages.innerHTML = voterid;

	</script>

	<div id="prime">prime or not</div>
	<script type="text/javascript">
		var prime = document.getElementById('prime');
		var number = prompt( );
		var numb;
		var findnum = number%2 ? numb = 'prime' : numb = 'not prime';
		prime.innerHTML = findnum //? 'allow' : 'denied'
		// prime.innerHTML += ',' + number;
	</script>
	<div id="statement">index</div>
	<script type="text/javascript">
		var userNames = ['mike','john','larry'];
		var userInput = prompt('what is your name');
		var checkUser = userNames.indexOf(userInput) >-1 ? true : false;
	    var statement = document.getElementById('statement');
		statement.innerHTML = checkUser ? 'welcome' : 'denied';
		// statement.innerHTML += ',' + userInput;
		
	</script>
	<div id="state">chemistry</div>
	<script type="text/javascript">
		var state = document.getElementById('state');
		var pages = ['liquid','solid','gas'];
		var react = prompt('what is given');
		var func = pages.indexOf(react) >-1 ? true : false;
		state.innerHTML = func ? 'welcome' : 'denied';

	</script>
</body>
</html>
