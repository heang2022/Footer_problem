<template>
    <section class="pt-8 text-lg-center" style="background-color: #F4F5F7">
        <v-container style="padding-bottom: 0px;">
            <v-row class="d-flex flex-row">
                <v-col sm="6" md="3" cols="12">
                    <div>
                        <h2 class="mb-4 display-1 font-weight-bold" style="margin-top: 25px">CASSTACK</h2>
                        <p class="mb-4 font-weight-bold title d-flex" style="margin-left: 85px; margin-top: -25px">Sale Booster</p>
                        <p class="title black--text font-weight-bold" style="margin-left: -260px; margin-top: 60px">Mission</p>
                        <p class="title black--text font-weight-regular text-lg-justify" style="margin-left: 0px; margin-top: 30px">Casstack is establish to grow
                            <br>Customer-Centric Business by<br>boosting up their sale online with<br>VoIP, Chatbot, Analytics and AI
                        </p>
                    </div>
                </v-col>
                <v-col sm="6" md="3" cols="12">
                    <div>
                        <h2 class="mb-4 display-1 font-weight-bold" style="margin-top: 25px">Contact Us</h2>
                        <hr class="blue d-flex" width="40px" style="hight: 2px; margin-left: 130px; margin-top: -10px">
                        <p class="title black--text font-weight-bold" style="margin-left: 50px;margin-top: 65px">Casstack Co., Pte. Ltd.</p>
                        <div class="d-flex" style="margin-left: 100px;">
                            <v-icon style="color: #55ACEE; margin-right: -120px" class="c1 d-flex">placement</v-icon>
                            <p class="black--text text-lg-justify" style="margin-left: 40px; margin-top: 30px; font-size: 15px; font-family: 'Roboto', sans-serif">#12, Street 2001, Phum Paprak Khang<br>
                                Tboung, Sangkat Kakab, Khan<br>Porsenchey, Phnom Penh, Cambodia
                            </p>
                        </div>
                        <div class="d-flex" style="margin-left: 100px">
                            <v-icon style="color: #55ACEE; margin-left: -60px" class="c1">call</v-icon>
                            <p class="black--text font-weight-regular text-lg-justify" style="margin-left: -50px; margin-top: 10px;font-size: 15px; font-family: 'Roboto', sans-serif">+855 96 911 6767
                            </p>
                        </div>
                        <div class="d-flex" style="margin-left: 100px">
                            <v-icon style="color: #55ACEE; margin-left: -50px" class="c1">email</v-icon>
                            <p class="black--text font-weight-regular text-lg-justify" style="margin-left: -40px; margin-top: 10px; font-size: 15px; font-family: 'Roboto', sans-serif">sales@casstack.com
                            </p>
                        </div>
                        <div class="d-flex" style="margin-top: 50px">
                            <nuxt-link to="#" class="black--text" style="text-decoration: none;font-size: 10px; font-family: 'Roboto', sans-serif; margin-left: 130px; text-decoration: underline">
                                <p>Term and Privacy</p>
                            </nuxt-link>
                            <nuxt-link to="#" class="black--text" style="text-decoration: none; font-size: 10px; font-family: 'Roboto', sans-serif; margin-right: 130px; text-decoration: underline">
                                <p>Report Abuse</p>
                            </nuxt-link>
                        </div>
                        <p style="text-decoration: none; font-size: 10px; font-family: 'Roboto', sans-serif; margin-top: -10px">Copyright &copy; 2020 - Present by Casstack Co., Pte. Ltd.</p>
                    </div>
                </v-col>
                <v-col sm="6" md="3" cols="12">
                    <div>
                        <h2 class="mb-4 display-1 font-weight-bold" style="margin-top: 25px">Follow Us</h2>
                        <hr class="blue d-flex" width="40px" style="hight: 2px; margin-left: 115px; margin-top: -10px">
                        <p class="title black--text font-weight-bold text-lg-justify" style="margin-left: 115px ;margin-top: 65px">Follow us anywhere with <br> @CasstackCompany</p>
                        <div>
                            <a href="#" target="_blank" class="black--text" style="text-decoration: none">
                                <v-btn icon id="Twitter">
                                    <v-icon>mdi-twitter</v-icon>
                                </v-btn>
                            </a>
                            <a href="#" target="_blank" class="black--text" style="text-decoration: none">
                                <v-btn icon id="Facebook">
                                    <v-icon>mdi-facebook</v-icon>
                                </v-btn>
                            </a>
                            <a href="#" target="_blank" class="black--text" style="text-decoration: none">
                                <v-btn icon id="LinkedIn">
                                    <v-icon>mdi-linkedin</v-icon>
                                </v-btn>
                            </a>
                        </div>
                    </div>
                </v-col>
            </v-row>
        </v-container>
    </section>
</template>
<script></script>
<style>
    .Btn {
        background-color: white;
    }
    #Twitter:hover {
        color: white;
        background-color: RGB(29, 161, 242);
    }
    #Facebook:hover {
        color: white;
        background-color: RGB(59, 89, 152);
    }
    #LinkedIn:hover {
        color: white;
        background-color: RGB(40, 103, 178);
    }
    .mb-4{
        color: #0D47A1

    }
</style>
