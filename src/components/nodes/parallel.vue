<template>
    <g>
        <rect :width="width" :height="height" :x="x-width/2" :y="y-height/2" rx="2" ry="2" stroke-width="2" fill="transparent" stroke-dasharray="0" />
        <text :x="x" :y="y+2" text-anchor="middle" font-size="14" stroke-width="0">
            <slot></slot>
        </text>
        <!-- <image xlink:href="../assets/branch.png" :x="x-width/2+2" :y="y-height/2+2" height="18" width="18" /> -->
        <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" :x="x-width/2+2" :y="y-height/2+2" height="18" width="18" viewBox="0 0 1000 1000" enable-background="new 0 0 1000 1000" xml:space="preserve">
            <metadata> Svg Vector Icons : http://www.sfont.cn </metadata>
            <g>
                <g transform="translate(0.000000,511.000000) scale(0.100000,-0.100000)">
                    <path d="M7294.9,4742.1l-289.1-267.9l507.6-532.3l511.2-535.8l-518.2-21.2c-740.3-28.2-1159.8-158.6-1699.2-525.3c-239.7-162.2-698-638.1-828.4-860.1c-52.9-88.1-98.7-162.2-105.8-162.2c-3.5,0-52.9,67-105.8,151.6c-324.3,500.6-690.9,842.5-1149.2,1082.2c-384.2,197.4-733.2,282-1276.1,306.7l-454.8,21.1l532.3,532.3l532.3,532.3l-257.3,257.3c-141,137.5-271.4,253.8-289.1,253.8c-21.2,0-493.5-458.3-1054-1018.8L332.7,2933.7l250.3-275c137.5-151.6,595.8-620.4,1018.8-1039.9l768.5-768.5l260.9,285.5l260.9,285.5l-208,215c-112.8,119.9-359.6,373.7-542.9,564l-334.9,341.9h437.1c490,0,733.2-49.4,1092.8-222.1c331.4-162.2,722.7-557,895.4-909.5c236.2-482.9,236.2-447.7,236.2-3475.8v-2725h405.4h405.4v2760.2c0,3021.1-3.5,2950.6,211.5,3391.2c229.1,472.4,705,895.4,1202.1,1075.2c193.8,70.5,310.2,84.6,842.5,95.2l616.9,14.1l-564-564l-564-567.6l282-282l282-282l1039.9,1039.9l1039.9,1039.9L8627.4,3970.1L7587.5,5010L7294.9,4742.1z" />
                </g>
            </g>
        </svg>
    </g>
</template>
<script>
export default {
    props: ['x', 'y', 'width', 'height'],
};
</script>