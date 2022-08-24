<template>
    <div class="second" >
        <h1 :style="{fontSize: 25+'px',fontFamily: 'Silkscreen',textAlign: 'center',letterSpacing: '2px'}">About Me</h1>
        <div id="academic" :style="{ padding: '15px',marginTop: '10px' }">
            <h2 :style="{ letterSpacing: '2px',fontSize: '20px',fontFamily: 'Silkscreen' }">Academics</h2>
            <div class="listAcademis">
                <ul :style="{padding: '5px 10px',letterSpacing: 1+'px',fontFamily: 'Poppins'}">
                    <div :style="{ margin: '10px 5px' }">
                        <li :style="{ color: 'red',fontWeight: 'bold',fontSize: '18px' }">2009-2010</li>
                        <p :style="{ margin: 'auto 10px',fontSize: '15px' }">TK Pertiwi Glempang</p>
                    </div>
                    <div :style="{ margin: '10px 5px' }">
                        <li :style="{ color: 'yellow',fontWeight: 'bold',fontSize: '18px' }">2009-2010</li>
                        <p :style="{ margin: 'auto 10px',fontSize: '15px' }">MI Darwata Glempang</p>
                    </div>
                    <div :style="{ margin: '10px 5px' }">
                        <li :style="{ color: 'green',fontWeight: 'bold',fontSize: '18px' }">2009-2010</li>
                        <p :style="{ margin: 'auto 10px',fontSize: '15px' }">SMP N 1 Maos</p>
                    </div>
                    <div :style="{ margin: '10px 5px' }">
                        <li :style="{ color: 'blue',fontWeight: 'bold',fontSize: '18px' }">2009-2010</li>
                        <p :style="{ margin: 'auto 10px',fontSize: '15px' }">SMA N 1 Maos</p>
                    </div>
                </ul>
            </div>
        </div>
    </div>
</template>