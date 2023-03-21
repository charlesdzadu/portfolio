<template>
    <div class="bg-[#0F0F0F] py-5 lg:h-screen">
        <div class="max-w-screen-2xl mx-auto  ">
            <div class="flex flex-col">
                <section class="flex flex-col lg:flex-row">
                    <div class="w-full lg:w-1/2 m-2 lg:order-1">
                        <div class=" flex flex-col gap-3">
                            <div class="bg-[#1E1B1E] p-4 flex justify-between rounded-2xl">
                                <div class="text-white">
                                    Charles<span class="font-black">Dzadu</span>
                                </div>
                                <div class="text-white cursor-pointer md:hidden" @click="toggleMenu">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                                        stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M4 6h16M4 12h16M4 18h16" />
                                    </svg>
                                </div>
                            </div>
                            <div class="flex flex-col md:flex-row justify-between gap-2 ">
                                <div class="bg-[url('~/assets/images/profil_charles.jpg')] w-full bg-cover rounded-2xl min-h-[400px] md:min-h-[200px]">

                                </div>
                                <div class="w-full flex flex-col gap-4">
                                    <div class="bg-[#1E1B1E] p-4 flex justify-between rounded-2xl">
                                        <div class="text-[#B1AFB2] text-sm">
                                            Nom:
                                        </div>
                                        <div class="text-white">
                                            <h2 class="text-md">Charles DZADU</h2>
                                        </div>
                                    </div>
                                    <div class="bg-[#1E1B1E] p-4 flex flex-col rounded-2xl">
                                        <div class="  flex justify-between ">
                                            <div class="text-[#B1AFB2] text-sm">
                                                Pays:
                                            </div>
                                            <div class="text-white">
                                                <h2 class="text-md">TOGO</h2>
                                            </div>
                                        </div>
                                        <div class=" flex justify-center items-center">
                                            <img src="~/assets/images/location.webp" alt="Location" class="h-64">
                                        </div>
                                    </div>
                                    <div class="bg-[#1E1B1E] p-1 flex justify-around rounded-2xl">
                                        <div class="h-16 w-16 bg-[#272427] rounded-full flex justify-center items-center cursor-pointer">
                                            <img src="~/assets/icons/linkedin.svg" alt="LinkedIn"
                                                class="text-white h-10 w-10">
                                        </div>
                                        <div class="h-16 w-16 bg-[#272427] rounded-full flex justify-center items-center">
                                            <img src="~/assets/icons/dribble.svg" alt="Dribble"
                                                class="text-white h-10 w-10">
                                        </div>
                                        <div class="h-16 w-16 bg-[#272427] rounded-full flex justify-center items-center">
                                            <img src="~/assets/icons/twitter.svg" alt="Twitter"
                                                class="text-white h-10 w-10">
                                        </div>
                                        <div class="h-16 w-16 bg-[#272427] rounded-full flex justify-center items-center">
                                            <img src="~/assets/icons/instagram.svg" alt="Instagram"
                                                class="text-white h-10 w-10">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class=" flex flex-col w-full lg:w-1/2 m-2">
                        <div class="bg-[#1E1B1E] flex flex-col h-full w-full p-5 rounded-2xl">
                            <h1 class="text-2xl md:text-6xl text-white mb-5 font-bold">Donner vie à vos idées grâce à la conception
                                d'interface utilisateur !</h1>
                            <button class="bg-[#8325FD] px-5 py-2 text-white rounded-md flex-end font-bold">Discutons affaire ✌
                            </button>
                        </div>
                        <div class=" h-full w-full flex flex-col md:flex-row justify-between gap-4 pt-4">
                            <div class="bg-[#00C39A] flex flex-col align-middle justify-center w-full rounded-2xl py-10">
                                <h1 class="text-2xl md:text-4xl text-center text-white font-black">5+</h1>
                                <p class="text-center text-white">Ans d'expérience</p>
                            </div>
                            <div class="bg-[#FFC03C] flex flex-col align-middle justify-center w-full rounded-2xl py-10">
                                <h1 class="text-2xl md:text-4xl text-center font-black">54+</h1>
                                <p class="text-center">Projets réalisées</p>
                            </div>
                            <div class="bg-[#FE6D79] flex flex-col align-middle justify-center w-full rounded-2xl py-10">
                                <h1 class="text-2xl md:text-4xl text-center text-white font-black">40+</h1>
                                <p class="text-center text-white">Clients</p>
                            </div>
                        </div>
                    </div>

                </section>
                <section class="flex flex-col lg:flex-row">
                    <div class=" bg-[#1E1B1E] p-4 rounded-2xl flex flex-col w-full lg:w-2/5 m-3 order-1">
                        <div class=" flex justify-between mb-4">
                            <div class="text-white">
                                <h2 class="text-md font-bold">A Propos</h2>
                            </div>
                            <div class="text-[#B1AFB2] text-sm group hover:text-white relative">
                                Curriculum Vitae
                                <span class="hidden absolute group-hover:flex focus:flex -left-5 -top-2 -translate-y-full w-48 px-2 py-1 bg-gray-700 rounded-lg text-center text-white text-sm after:content-[''] after:absolute after:left-1/2 after:top-[100%] after:-translate-x-1/2 after:border-8 after:border-x-transparent after:border-b-transparent after:border-t-gray-700"> Mon curriculum vitae est disponible sur Github </span>
                            </div>
                            
                        </div>
                        <div class=" h-full w-full text-justify text-[#9E9B9E] font-light text-sm">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis distinctio hic, voluptate nobis eveniet tempore velit quis inventore. Placeat, nulla accusamus reprehenderit facilis officia totam. Iste, reiciendis! Consequatur, recusandae expedita? nulla accusamus reprehenderit facilis officia totam. Iste, reiciendis! Consequatur, recusandae expedita? <br>
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facilis distinctio hic, voluptate nobis eveniet tempore velit quis inventore. 
                        </div>
                    </div>
                    <div class="bg-[#1E1B1E] p-4 rounded-2xl flex flex-col w-full lg:w-3/5 m-3">
                        <div class=" flex justify-between mb-4">
                            <div class="text-white">
                                <h2 class="text-md font-bold">UI Portfolio</h2>
                            </div>
                            <div class="text-[#B1AFB2] text-sm">
                                Tous voir
                            </div>
                            
                        </div>
                        <div class="h-full w-full flex flex-col md:flex-row justify-between gap-2 pt-2">
                            <div class=" w-full rounded-2xl">
                                <div class="relative  md:h-40"> 
                                    <img src="https://cdn.dribbble.com/userupload/3284122/file/original-7648ab335ef534aa085dc038ce4d5d78.png?resize=400x0" alt="Projet 1" class=" bg-cover rounded-2xl w-full md:h-40">

                                    <div class="absolute  top-0 left-0 w-full h-full bg-[#1E1B1E] opacity-50"></div>

                                </div>
                            </div>
                            <div class=" w-full rounded-2xl">
                                <div class="relative md:h-40"> 
                                    <img src="https://img.freepik.com/free-vector/various-screens-violet-public-transport-mobile-app_23-2148704862.jpg" alt="Projet 1" class="w-full bg-cover rounded-2xl md:h-40">

                                    <div class="absolute  top-0 left-0 w-full h-full bg-[#1E1B1E] opacity-50"></div>

                                </div>
                            </div>
                            <div class=" w-full rounded-2xl">
                                <div class="relative md:h-40"> 
                                    <img src="https://speckyboy.com/wp-content/uploads/2020/11/free-mobile-ui-kit-th.jpg" alt="Projet 1" class=" bg-cover rounded-2xl w-full md:h-40">

                                    <div class="absolute  top-0 left-0 w-full h-full bg-[#1E1B1E] opacity-50"></div>

                                </div>
                            </div>
                        </div>
                    </div>
                    
                </section>

            </div>
        </div>

        <div ref="sideMenu" class="fixed top-0 left-[-300px] w-[300px] bg-[#1E1B1E] flex flex-col text-white h-full p-5 space-y-5 my-6 rounded-2xl duration-300">
            <div class="flex justify-between">
                <h1 class="text-white text-xl font-bold">Menu Général</h1>
                <p @click="toggleMenu" class="cursor-pointer"> Close</p>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'Home',
    data() {
        return {
            showMenu: false,
        }
    },
    methods: {
        toggleMenu() {
            this.showMenu = !this.showMenu
            if (this.showMenu) {
                this.$refs.sideMenu.style.left = '0px'
            } else {
                this.$refs.sideMenu.style.left = '-300px'
            }
        }
    }
}

</script>


