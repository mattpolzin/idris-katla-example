<style>
.IdrisData {
  color: darkred
}
.IdrisType {
  color: blue
}
.IdrisBound {
  color: black
}
.IdrisFunction {
  color: darkgreen
}
.IdrisKeyword {
  text-decoration: underline;
}
.IdrisComment {
  color: #b22222
}
.IdrisNamespace {
  font-style: italic;
  color: black
}
.IdrisPostulate {
  font-weight: bold;
  color: red
}
.IdrisModule {
  font-style: italic;
  color: black
}
.IdrisCode {
  display: block;
  background-color: whitesmoke;
}
</style>
A Homepage!
=========

Something interesting.

## A section
Contents of that section.

A [link](/other)

## Some code

<code class="IdrisCode">
<span class="IdrisKeyword">data</span>&nbsp;<span class="IdrisType">Greeting</span>&nbsp;<span class="IdrisKeyword">=</span>&nbsp;<span class="IdrisData">Hello</span>&nbsp;<span class="IdrisKeyword">|</span>&nbsp;<span class="IdrisData">Hi</span><br />
<br />
<span class="IdrisType">Show</span>&nbsp;<span class="IdrisType">Greeting</span>&nbsp;<span class="IdrisKeyword">where</span><br />
&nbsp;&nbsp;<span class="IdrisFunction">show</span>&nbsp;<span class="IdrisData">Hello</span>&nbsp;<span class="IdrisKeyword">=</span>&nbsp;<span class="IdrisData">&quot;hello&quot;</span><br />
&nbsp;&nbsp;<span class="IdrisFunction">show</span>&nbsp;<span class="IdrisData">Hi</span>&nbsp;&nbsp;&nbsp;&nbsp;<span class="IdrisKeyword">=</span>&nbsp;<span class="IdrisData">&quot;hi&quot;</span><br />
</code>

