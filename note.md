```HTML

<p v-if="seen">Now you see me</p>

<a v-bind:href="url"> ... </a>

<a v-on:click="doSomething"> ... </a>


<!-- full syntax -->
<a v-bind:href="url"> ... </a>

<a v-bind:[attributeName]="url"> ... </a>

<a v-on:[eventName]="doSomething"> ... </a>

<form v-on:submit.prevent="onSubmit">...</form>


<!-- shorthand -->
<a :href="url"> ... </a>

<!-- shorthand with dynamic argument -->
<a :[key]="url"> ... </a>

<p v-if="seen">Now you see me</p>

<a v-bind:href="url"> ... </a>

<a v-on:click="doSomething"> ... </a>

<a v-bind:[attributeName]="url"> ... </a>

<a v-on:[eventName]="doSomething"> ... </a>

<form v-on:submit.prevent="onSubmit">...</form>

<!-- full syntax -->
<a v-bind:href="url"> ... </a>

<!-- shorthand -->
<a :href="url"> ... </a>

<!-- shorthand with dynamic argument -->
<a :[key]="url"> ... </a>


<!-- full syntax -->
<a v-on:click="doSomething"> ... </a>

<!-- shorthand -->
<a @click="doSomething"> ... </a>

<!-- shorthand with dynamic argument -->
<a @[event]="doSomething"> ... </a>


<!-- This will trigger a compiler warning. -->
<a v-bind:['foo' + bar]="value"> ... </a>

<a v-bind:[someAttr]="value"> ... </a>


<button @click="increment">Up vote</button>







```