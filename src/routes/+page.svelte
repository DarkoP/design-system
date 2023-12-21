<script>
	import InputButton from './components/InputButton.svelte';
	import InputCheckbox from './components/InputCheckbox.svelte';
	import InputColor from './components/InputColor.svelte';
	import InputDate from './components/InputDate.svelte';
	import InputDatetimeLocal from './components/InputDatetimeLocal.svelte';
	import InputEmail from './components/InputEmail.svelte';
	import InputFile from './components/InputFile.svelte';
	import InputImage from './components/InputImage.svelte';
</script>

<section>
    <header>
        <h1>All HTML Form Elements</h1>
    </header>

    <div>
        <InputButton />
    </div>
    <div>
        <InputCheckbox />
    </div>
    <div>
        <InputColor />
    </div>
    <div>
        <InputDate />
    </div>
    <div>
        <InputDatetimeLocal />
    </div>
    <div>
        <InputEmail />
    </div>
    <div>
        <InputFile />
    </div>
    <div>
        <InputImage />
    </div>

</section>

<style>
    header {
        display: flex;
        justify-content: center;
    }
    section {
		display: flex;
		flex-direction: column;
        gap: 2rem;
	}
</style>


