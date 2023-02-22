<script>
	let p = '<p>';
	let endp = '</p>';
	let h1 = '<h1>';
	let endh1 = '</h1>';
</script>

<head>
	<title>About - Mathias Ödlund</title>
	<meta
		name="description"
		content="I am a Norwegian-based web developer and automation engineer with a passion for solving complex problems with new and modern cloud solutions."
	/>
</head>
<section class="w-full lg:w-1/3 md:w-2/3 sm:w-full p-10 md:p-0 mx-auto transitionIn">
<div class="nested flex flex-col w-48 mx-auto mb-8 mt-6">
    <p class="fakeh1 -ml-4">{h1}</p>
    <h1 class="text-white font-bold text-3xl mb-2 flex self-center md:self-center sm:self-center">About me</h1>
    <p class="fakeh1 self-end"> {endh1}
    </p>

</div>
<div class="nested flex flex-col">
    <p class="fakep">{p}</p>
    <p class="mb-4">	I am a Norwegian-based web developer and automation engineer with a
        passion for solving complex problems with new and modern cloud solutions.</p>
        <p class="mb-2">	As a seasoned software developer with four years of experience as a freelancer, I have had the privilege of collaborating with a diverse range of startups, local companies, and other clients. My expertise lies in full-stack web development, and I am well-versed in employing a variety of tools to build robust web applications. My versatility extends to programming languages and frameworks, enabling me to adapt to the unique requirements of each project with ease.</p>
            <p>Presently, I am proud to be a valuable contributor to the team at Evolo Technologies.



            </p>
            <p class="fakep self-end">{endp}</p>
</div>
</section>
<style>
	@import url('https://fonts.googleapis.com/css2?family=Rancho&display=swap');
	.fakep {
		color: rgb(126, 126, 126);
		font-family: 'Rancho', cursive;
		font-size: 25px;
		letter-spacing: 1px;
		font-style: italic;
		margin-left: -20px;
		padding: 2px;
	}
	.fakeh1 {
		color: rgb(126, 126, 126);
		font-family: 'Rancho', cursive;
		font-size: 25px;
		letter-spacing: 1px;
		font-style: italic;
		padding: 2px;
	}
	@keyframes transitionIn {
		from {
			opacity: 50%;
			transform: rotateX(-5deg);
		}
		to {
			opacity: 100%;
			transform: rotateX(0);
		}
	}
	.info {
		animation: transitionIn 0.75s;
	}
</style>