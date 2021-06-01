<template>
    <vue-navigation-bar :options="options" />
</template>

<script>
    
</script>

<style lang="scss">
    .vnb {
        .button-red {
            background: #FF3B30;

            &:hover {
                background: darken(#FF3B30, 10%);
            }
        }
    }
</style>

<script src="https://unpkg.com/vue-navigation-bar@1.0.0/dist/vue-navigation-bar.min.js"></script>


<script>


// import VueNavUI from "vue-nav-ui";

// import { defineComponent, ref } from "vue";
// export default defineComponent({
//   name: 'home',
//   components: {
//     VueNavUI
//   },
//   setup(){
//     const navLinks = ref([
//       {
//         name: "Home",
//         path: "/",
//       },
//       {
//         name: "About",
//         path: "/about",
//       },
//       {
//         name: "FAQs",
//         path: "/faqs",
//       },
//       {
//         name: "More",
//         path: "/more",
//       },
//       {
//         name: "Media",
//         path: "/media",
//       }
//     ]);

//     const navConfig = ref({
//       whitespace: true,
//       navBg: "#FAFAFA",
//       navBorderRadius: "30px",
//       linkFont: "poppins",
//       linkColor: "black",
//       responsivePosition: "top or bottom"
//     });

//     const btnConfig = ref({
//       btnLink: true,
//       btnUrl: "https://dhaniel.disha.page",
//       btnText: "Download app",
//       btnBg: "#40269E",
//       btnTextColor: "White",
//       btnBorderWidth: "0",
//       btnBorderColor: "Black",
//       btnBorderRadius: "20px",
//     });

//     return {navLinks, btnConfig, navConfig};
//   }
// });

export default {
        ...
        data () {
            return {
                navbarData: {
                    elementId: 'main-navbar',
                    isUsingVueRouter: true,
                    mobileBreakpoint: 992,
                    brandImagePath: '/',
                    brandImage: require('../src/assets/images/lockup-color.png'),
                    brandImageAltText: 'vue-navigation-bar',
                    collapseButtonStyle: 'dark',
                    ariaLabelMainNav: 'Main Navigation',
                    menuOptionsLeft: [
                        {
                            type: 'link',
                            text: 'Why Dunder Mifflin',
                            path: '/why',
                            subMenuOptions: [
                                {
                                    type: 'link',
                                    text: 'About',
                                    path: '#',
                                },
                                {
                                    type: 'hr',
                                },
                                {
                                    type: 'link',
                                    text: 'Locations',
                                    path: '/locations',
                                },
                                {
                                    type: 'link',
                                    text: 'Blog',
                                    path: '/blog',
                                },
                            ]
                        },
                        {
                            type: 'link',
                            text: 'Contact',
                            path: '/contact',
                            subMenuOptions: [
                                {
                                    type: 'link',
                                    text: 'Customer Service',
                                    path: '/customer-service',
                                },
                                {
                                    type: 'link',
                                    text: 'Accounting',
                                    path: '/accounting',
                                },
                                {
                                    type: 'link',
                                    text: 'Reception',
                                    path: '/reception',
                                },
                            ]
                        },
                        {
                            type: 'link',
                            text: 'Pricing',
                            path: '/pricing',
                        },
                    ],
                    menuOptionsRight: [
                        {
                            type: 'button',
                            text: 'Signup',
                            path: '/signup',
                            class: 'button-red'
                        },
                        {
                            type: 'button',
                            text: 'Login',
                            path: '/login',
                        }
                    ]
                }
            }
        }
        ...
    }

</script>
<style lang="scss" scoped>

  
  </style>
  <script src="https://unpkg.com/vue-navigation-bar@1.0.0/dist/vue-navigation-bar.min.js"></script>

