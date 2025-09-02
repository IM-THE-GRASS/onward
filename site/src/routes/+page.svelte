<script>
    import Circuits from './Circuts.svelte';
    import RobotHead from './RobotHead.svelte';
</script>




<div class="bg-[rgb(0,0,2)] h-[500vh]">
    <div class="w-full h-[100vh] relative content-center flex flex-col items-center justify-center">
        <div class="flex flex-row items-center mt-[-20vh] z-2">
            <h1 class="title mx-[2vw]">ONWARD</h1>
        </div>
        <div class="flex flex-row mt-[2vh] justify-center items-center z-2">
            <p class="">Build a </p>
            <span class="font-bold embold mx-[1.5vh]">robot,</span>
            <p> get a grant to build it</p>
            <span class="font-bold embold mx-[1.5vh]">in real life.</span>

        </div> 
        <div class="absolute z-1 fill-black opacity-50">
            <Circuits />
            <RobotHead />
        </div>
    </div>
    
</div>
