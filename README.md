<h1>Get Browser</h1>

A jQuery plugin to display a countdown timer.

<h3>Demo</h3>
<a href="http://spedwards.github.io/projects/countdown/">Countdown</a>

<h2>Usage</h2>

<p>The syntax is very simple. Just use</p>
<pre><code>$(selector).countdown(<a href="#options">options</a>);</code></pre>
<p>to generate a countdown timer. If the selected element already has a countdown, the previous one will be overwritten.

<h2 id="options">Options</h2>

<p>The available options and their default values are:</p>
<pre><code>
{
	// the time to count from
	hours : 0,
	minutes : 0,
	seconds : 0,
	milliseconds : 0,
							
	// function to run when done
	done : function(){},
	
	// whether to count down or up
	reverse : false
}
</code></pre>
