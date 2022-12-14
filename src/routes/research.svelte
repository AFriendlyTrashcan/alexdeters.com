<script>
	import { variants } from '@catppuccin/palette';
	let selected = 'latte';
</script>

<svelte:head>
	<title>Research | Alexander Deters</title>
</svelte:head>

<html lang="en" class={selected ? selected : ''}>
    <body class="latte bg-base">
        <div class="mx-6 md:mx-20 lg:mx-[30rem] my-6 md:mt-8 font-proxima text-text">
            <h1 class="h-14 text-5xl text-center md:text-left font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-pink to-mauve">Research</h1>
            <hr class="h-[0.1rem] border-0 bg-surface2 my-4">
            <div class="font-thin">
                <h2 class="text-2xl font-bold">RFSoC Based Quantum Control</h2>
                <h3 class="text-l font-semibold mt-1 hidden md:block">Prof Rob Schoelkopf, <em>Yale University</em> (September 2021 - Present)</h3>
                <h3 class="text-l font-semibold mt-1 md:hidden">Prof Rob Schoelkopf, <em>Yale University</em> <br>(September 2021 - Present)</h3>
                <p class="mt-4"> We are developing a new RFSoC based control system for use in RSL and <a class="text-mauve" href="https://qulab.eng.yale.edu/">Michel Devoret's Group</a>. Wrote and debugged <b class="font-bold">VHDL</b> code pertaining to the signal generation capabilities of the system. Worked on <b class="font-bold">Linux</b> system programming and its interactions with low level FPGA design. Collaboration with <a class="text-mauve" href="https://quantumcircuits.com/">Quantum Circuits Inc</a>.<br><br>

                    This project further provided an opportunity for learning about <b class="font-bold">pulse engineering</b> for superconducting circuits, and techniques for high fidelity quantum control. Also gained practical experience in collaborating between academia and industry.
                </p>
            <hr class="h-[0.1rem] border-0 bg-surface2 my-4">
                <h2 class="text-2xl font-bold">Microwave Signal Generation Nonlinearities</h2>
                <h3 class="text-l font-semibold mt-1 hidden md:block">Prof Rob Schoelkopf, <em>Yale University</em> (October 2021 - Present)</h3>
                <h3 class="text-l font-semibold mt-1 md:hidden">Prof Rob Schoelkopf, <em>Yale University</em> <br>(October 2021 - Present)</h3>
                <p class="mt-4">Personally investigating various techniques and limitations in modeling nonlinearities for microwave <b class="font-bold">digital to analog converters</b>. Further researched techniques in digital predistortion applied to signal generation, with preliminary results showing a <b class="font-bold">15 - 20dB improvement</b> in spurious free dynamic range.<br><br>

                    Project provided an opportunity to learn about <b class="font-bold"> nonlinear circuit analysis </b> as well as gained a better understanding of lesser known nonidealities in a standard fridge RF stack. <br><br>

                    I will be giving a talk about the results at the <b class="font-bold">2023 APS March Meeting</b> titled "Characterization and Suppression of Nonlinearities in a Quantum Control System Employing Direct Digital Synthesis."
                </p>
            <hr class="h-[0.1rem] border-0 bg-surface2 my-4">
                <h2 class="text-2xl font-bold">Real Time Surface Code Decoding</h2>
                <h3 class="text-l font-semibold mt-1 hidden md:block">Lin Zhong and Rob Schoelkopf, <em>Yale University</em> (May 2021 - Present)</h3>
                <h3 class="text-l font-semibold mt-1 md:hidden">Lin Zhong and Rob Schoelkopf, <em>Yale University</em> <br>(May 2021 - Present)</h3>
                <p class="mt-4"> Created algorithm to apply graph theory principles in automatically computing optimal arrangement of FPGAs for lowering latency in a distributed surface code decoding algorithm. Developed <b class="font-bold">Python</b> software to automatically generate synthesizable <b class="font-bold">Verilog</b> hardware design files to this end.<br><br>

                    Wrote novel analytic proof of average time complexity for a class of decoders for surface code syndromes. Developed <b class="font-bold">VHDL</b> module and <b class="font-bold">Vivado</b> hardware design for benchmarking communication protocols to nanosecond accuracy.<br><br>

                    <b class="font-bold">Co-authored</b> a talk at the 2023 APS March Meeting titled "Distributed union find decoder and its FPGA based implementation for scalable error correction."
                </p>
            </div>
        </div>
	</body>
</html>
