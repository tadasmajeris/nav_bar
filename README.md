# nav_bar_script

<script>
  $.each($('.nav').find('a'), function() {
    $(this).parent().addClass(this.pathname === window.location.pathname ? 'active' : '/');
  });
</script>
