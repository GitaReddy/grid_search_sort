<script>
	import Grid from "gridjs-svelte"
  
	const data = [
		
		{name: "vicky", email: "vicky@gmail.com", city:"NewYork" },
		{name: "vicky drawn", email: "vicky02@gmail.com", city:"Sydney" },
		{name: "daniel", email: "danielvicky@gmail.com", city:"Manchester" },
		{name: "John Doe", email: "john@gmail.com", city:"NewYork" },
		{name: "Jane Smith", email: "jane@gmail.com", city:"London" },
		{name: "Bob Johnson", email: "bob.john@gmail.com", city:"NewYork" },
		{name: "Vicky Vikram", email: "vicky.viki@gmail.com", city:"NewYork" },
		{name: "Boby", email: "boby123@gmail.com", city:"Melborne" },
		{name: "Daniel Brown", email: "brown@gmail.com", city:"Washington" }
]

  </script>
  
  <Grid 
  sort
  search 
  filter
  
  data={data}/>
  
  <style global>
	@import "https://cdn.jsdelivr.net/npm/gridjs/dist/theme/mermaid.min.css";
  </style>

<!-- pagination={{ enabled: true, limit: 5 }} -->