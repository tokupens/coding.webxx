$('a.js-scroll-trigger[href*="#"]:not([href="#"])').click(function() 
{
  if (location.pathname.replace(/^\//, '') == this.pathname.replace(/^\//, '') && location.hostname == this.hostname) 
  {
    var target = $(this.hash);
    target = target.length ? target : $('[name=' + this.hash.slice(1) + ']');
    if (target.length) 
    {
      $('html, body').animate(
      {
        scrollTop: (target.offset().top - 71)
      }, 1000, "easeInOutExpo"); 

      return false;
    }
  }
});

$(document).scroll(function() 
{
  let scrollDistance = $(this).scrollTop();
  if (scrollDistance > 100) 
      $('.scroll-top').fadeIn();
  else 
      $('.scroll-top').fadeOut();
});

$('.scroll-top').click(function()
{
  $('html, body').animate({scrollTop: 0}, 500)
});

$('.input-form').focus(function()
{
  $(this).css("box-shadow", "2px 2px 3px 0.5px rgba(0.9,0.9,0.9, 0.2)");
  $(this).css("border-color", "rgb(66,180,205)");
});

$('.input-form').blur(function()
{
  $(this).css("box-shadow", "0px 0px 0px 0px #fff");
  $(this).css("border-color", "#aaa");
});


$(document).scroll(function() 
{
  let scrollDistance = $(this).scrollTop();
    let a = true;
  if (scrollDistance > 580 && a) 
  {
     $("#pro-1").animate({width: '90%'}, 50);
     $("#pro-2").animate({width: '80%'}, 50);
     $("#pro-3").animate({width: '88%'}, 50);
     $("#pro-4").animate({width: '90%'}, 50);

     $("#pro-5").animate({width: '90%'}, 50);
     $("#pro-6").animate({width: '85%'}, 50);
     $("#pro-7").animate({width: '80%'}, 50);
     $("#pro-8").animate({width: '92%'}, 50);

     $("#pro-9").animate({width: '45%'}, 50);
     $("#pro-10").animate({width: '80%'}, 50);
     $("#pro-11").animate({width: '83%'}, 50);
     $("#pro-12").animate({width: '85%'}, 50);
     a = false;
  }
});

$(document).ready(function() 
{
  let scrollDistance = $(document).scrollTop();
    let a = true;
  if (scrollDistance > 580 && a) 
  {
     $("#pro-1").animate({width: '90%'}, 50);
     $("#pro-2").animate({width: '80%'}, 50);
     $("#pro-3").animate({width: '88%'}, 50);
     $("#pro-4").animate({width: '90%'}, 50);

     $("#pro-5").animate({width: '90%'}, 50);
     $("#pro-6").animate({width: '85%'}, 50);
     $("#pro-7").animate({width: '80%'}, 50);
     $("#pro-8").animate({width: '92%'}, 50);

     $("#pro-9").animate({width: '45%'}, 50);
     $("#pro-10").animate({width: '80%'}, 50);
     $("#pro-11").animate({width: '83%'}, 50);
     $("#pro-12").animate({width: '85%'}, 50);
     a = false;
  }
});
