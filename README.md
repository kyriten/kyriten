
<div id="header" align="center">
  <svg width="311.572" height="158.716" viewBox="0 0 311.572 158.716" xmlns="http://www.w3.org/2000/svg">
	  <style>
		  /* Google chrome */
      @-webkit-keyframes svg-text-anim {
       40% {
          stroke-dashoffset: 0;
          fill: transparent;
        }
        60% {
          stroke-dashoffset: 0;
          fill: #6ed7f2;
        }
        100% {
          stroke-dashoffset: 0;
          fill: #6ed7f2;
        }
        
    }
    /* Most browsers */
    @keyframes svg-text-anim {
       40% {
          stroke-dashoffset: 0;
          fill: transparent;
        }
        60% {
          stroke-dashoffset: 0;
          fill: #6ed7f2;
        }
        100% {
          stroke-dashoffset: 0;
          fill: #6ed7f2;
        }
        
    }</style>
    <script>
    function setTextAnimation(delay, duration, strokeWidth, timingFunction, strokeColor,repeat) {
            let paths = document.querySelectorAll("path");
            let mode=repeat?'infinite':'forwards'
            for (let i = 0; i < paths.length; i++) {
                const path = paths[i];
                const length = path.getTotalLength();
                path.style["stroke-dashoffset"] = `${length}px`;
                path.style["stroke-dasharray"] = `${length}px`;
                path.style["stroke-width"] = `${strokeWidth}px`;
                path.style["stroke"] = `${strokeColor}`;
                path.style["animation"] = `${duration}s svg-text-anim ${mode} ${timingFunction}`;
                path.style["animation-delay"] = `${i * delay}s`;
            }
        }
 setTextAnimation(0.5,4,2,'ease-in','#ffffff',true);</script>
	<g id="svgGroup" stroke-linecap="round" fill-rule="evenodd" font-size="9pt" stroke="#000" stroke-width="0.25mm" fill="none" style="stroke:#000;stroke-width:0.25mm;fill:none">
		<path d="M 0 119.092 L 0 2.564 L 17.505 2.564 L 17.505 73.316 L 31.787 73.316 L 48.413 42.408 L 66.797 42.408 L 49.146 73.096 A 14.782 14.782 0 0 1 54.639 75.257 A 16.732 16.732 0 0 1 59.07 79.431 Q 60.938 81.958 62 85.144 A 21.069 21.069 0 0 1 63.052 91.25 A 23.883 23.883 0 0 1 63.062 91.919 L 63.062 106.568 L 79.907 106.568 A 14.741 14.741 0 0 1 78.479 111.438 Q 77.344 113.745 75.623 115.43 A 13.45 13.45 0 0 1 71.704 118.103 A 11.12 11.12 0 0 1 67.09 119.092 L 59.546 119.092 A 10.562 10.562 0 0 1 54.163 117.627 A 14.619 14.619 0 0 1 50.279 114.325 A 17.089 17.089 0 0 1 49.731 113.636 A 19.066 19.066 0 0 1 47.41 109.568 A 22.952 22.952 0 0 1 46.729 107.74 A 22.593 22.593 0 0 1 45.675 102.044 A 26.381 26.381 0 0 1 45.63 100.489 L 45.63 85.62 L 17.505 85.62 L 17.505 119.092 L 0 119.092 Z" id="0" vector-effect="non-scaling-stroke"/>
		<path d="M 92.505 100.489 L 92.505 42.408 L 110.01 42.408 L 110.01 106.568 L 140.186 106.568 L 140.186 42.408 L 157.69 42.408 L 157.69 106.568 L 172.485 106.568 A 14.741 14.741 0 0 1 171.057 111.438 Q 169.922 113.745 168.201 115.43 A 13.45 13.45 0 0 1 164.282 118.103 A 11.12 11.12 0 0 1 159.668 119.092 L 157.69 119.092 L 157.69 139.966 A 24.341 24.341 0 0 1 157.076 145.507 A 21.822 21.822 0 0 1 156.592 147.254 A 21.559 21.559 0 0 1 155.003 150.988 A 17.972 17.972 0 0 1 153.589 153.186 A 15.804 15.804 0 0 1 150.387 156.396 A 14.45 14.45 0 0 1 149.158 157.215 A 10.367 10.367 0 0 1 143.774 158.716 L 108.325 158.716 L 108.325 146.045 L 140.186 146.045 L 140.186 111.255 Q 138.208 114.917 135.095 117.005 A 12.21 12.21 0 0 1 131.047 118.799 A 11.348 11.348 0 0 1 128.467 119.092 L 106.421 119.092 Q 103.564 119.092 101.001 117.627 A 14.226 14.226 0 0 1 96.806 113.947 A 16.37 16.37 0 0 1 96.57 113.636 A 19.468 19.468 0 0 1 94.324 109.666 A 23.637 23.637 0 0 1 93.604 107.74 A 22.593 22.593 0 0 1 92.55 102.044 A 26.381 26.381 0 0 1 92.505 100.489 Z" id="1" vector-effect="non-scaling-stroke"/>
		<path d="M 185.889 119.092 L 185.889 34.351 L 203.467 34.351 L 203.467 42.408 L 258.691 42.408 A 14.741 14.741 0 0 1 257.263 47.278 A 15.282 15.282 0 0 1 255.203 50.446 A 13.843 13.843 0 0 1 254.443 51.27 A 13.113 13.113 0 0 1 250.598 53.943 A 10.544 10.544 0 0 1 246.167 54.932 L 246.167 106.568 L 263.159 106.568 A 14.741 14.741 0 0 1 261.731 111.438 A 14.146 14.146 0 0 1 259.055 115.217 A 13.461 13.461 0 0 1 258.838 115.43 A 13.646 13.646 0 0 1 254.81 118.103 Q 252.539 119.092 249.976 119.092 L 242.651 119.092 Q 239.795 119.092 237.231 117.627 A 14.562 14.562 0 0 1 233.127 114.1 A 16.844 16.844 0 0 1 232.764 113.636 A 19.066 19.066 0 0 1 230.442 109.568 A 22.952 22.952 0 0 1 229.761 107.74 A 22.593 22.593 0 0 1 228.707 102.044 A 26.381 26.381 0 0 1 228.662 100.489 L 228.662 54.932 L 203.32 54.932 L 203.32 119.092 L 185.889 119.092 Z" id="2" vector-effect="non-scaling-stroke"/>
		<path d="M 278.394 100.489 L 278.394 42.408 L 295.898 42.408 L 295.898 106.568 L 311.572 106.568 Q 311.353 109.131 310.217 111.438 Q 309.082 113.745 307.361 115.43 A 13.45 13.45 0 0 1 303.442 118.103 A 11.12 11.12 0 0 1 298.828 119.092 L 292.383 119.092 Q 289.526 119.092 286.963 117.627 A 14.562 14.562 0 0 1 282.858 114.1 A 16.844 16.844 0 0 1 282.495 113.636 A 19.066 19.066 0 0 1 280.174 109.568 A 22.952 22.952 0 0 1 279.492 107.74 A 22.593 22.593 0 0 1 278.439 102.044 A 26.381 26.381 0 0 1 278.394 100.489 Z M 282.517 23.874 A 12.171 12.171 0 0 0 286.963 24.683 A 12.188 12.188 0 0 0 291.724 23.731 A 12.206 12.206 0 0 0 295.679 21.094 A 12.832 12.832 0 0 0 298.352 17.176 Q 299.341 14.942 299.341 12.378 Q 299.341 9.815 298.352 7.581 A 12.832 12.832 0 0 0 295.679 3.662 A 12.832 12.832 0 0 0 291.76 0.989 Q 289.526 0 286.963 0 Q 284.399 0 282.166 0.989 A 12.832 12.832 0 0 0 278.247 3.662 A 12.312 12.312 0 0 0 275.61 7.581 A 11.699 11.699 0 0 0 275.467 7.932 A 12.171 12.171 0 0 0 274.658 12.378 A 13.765 13.765 0 0 0 274.658 12.458 A 12.087 12.087 0 0 0 275.61 17.176 A 12.312 12.312 0 0 0 278.247 21.094 A 12.312 12.312 0 0 0 282.166 23.731 A 11.699 11.699 0 0 0 282.517 23.874 Z" id="3" vector-effect="non-scaling-stroke"/>
	</g>
</svg>
</div>

### Hi there 👋

- 👋 Hi, I’m Abimanyu, called Abi (pronounced in Bahasa, please)
- 👀 Now i'm gaining my programming skills. Primary is C++ and Web Development
- 🌱 I’m currently learning html, css, js, c++
- 💞️ I’m a chairman of IEEE Student Branch Pakuan University for 2021-2022, who has my spirit in the programming world. They are my favorite in my college
- 📫 How to reach me. you can found me in instagram @ossastra or gmail (okysaputraa10@gmail.com)
- Hey let be my friends.
