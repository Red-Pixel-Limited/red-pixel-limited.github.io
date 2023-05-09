---
title: About
layout: home
cover: true
---

<!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" > -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.js"></script>

<style type="text/css" media="screen">
    h3 { margin: 3rem 0 1rem; } 
    .slick-slide{
        margin: 0 20px;
    }
    .slick-slide img{
        width: 100%;
    }
    .slick-slider{
        position: relative;
        display: block;
        box-sizing: border-box;
    }
    .slick-list{
        position: relative;
        display: block;
        overflow: hidden;
        margin: 0;
        padding: 0;
    }
    .slick-track{
        position: relative;
        top: 0;
        left: 0;
        display: block
    }
    .slick-slide{
        display: none;
        float: left;
        height: 100%;
        min-height: 1px;
    }
    .slick-slide img{
        display: block;
    }
    .slick-initialized .slick-slide{
        display: block;
    }
</style>

<img src="/assets/img/logo.png"  width="50%" height="25%">

The company was established on 19 February 2018 when the founder of the company, Mr. Sergejs Terentjevs, had already many years of experience in software design and development. He had developed banking systems which later were integrated into multiple banks, participated in trading systems development, designed and implemented machine travel document reading software and worked on multiple e-commerce systems.   
The ultimate goal was to become a consultant helping organisations to achieve their goals. That was successfully accomplished working on highly scalable systems design and implementation, client data migration, platform tasks and business requirements.   
[Learn more](/projects)

### Our Clients

<div style="padding-top: 50px">
    <section class="customer-logos slider">
        <div class="slide"><img src="assets/img/client/disneystreaming.png" alt="logo"></div>
        <div class="slide"><img src="assets/img/client/hmrc.png" alt="logo"></div>
        <div class="slide"><img src="assets/img/client/siriusxm.png" alt="logo"></div>
        <div class="slide"><img src="assets/img/client/ebay.png" alt="logo"></div>
        <div class="slide"><img src="assets/img/client/nutmeg.png" alt="logo"></div>
    </section>
</div>

### Useful Links

* <a href="https://github.com/Red-Pixel-Limited" target="_blank">GitHub page</a>
* <a href="https://find-and-update.company-information.service.gov.uk/company/11212396" target="_blank">Companies House page</a>

<script>
    $(document).ready(function(){
        $('.customer-logos').slick({
            slidesToShow: 4,
            slidesToScroll: 1,
            autoplay: true,
            autoplaySpeed: 1500,
            arrows: false,
            dots: false,
            pauseOnHover:false,
            responsive: [{
                breakpoint: 768,
                setting: {
                    slidesToShow:4
                }
            }, {
                breakpoint: 520,
                setting: {
                    slidesToShow: 3
                }
            }]
        });
    });
</script>
