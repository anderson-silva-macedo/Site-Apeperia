"# atividade-workflow"
"# atividade-workflow"



var browserSync = require('browser-sync').create();

// Static Server + watching scss/html files
gulp.task('serve', function() {

  browserSync.init({
      server: "./public"
  });

  gulp.watch("scss/**/*.scss", ['sass']);
  gulp.watch("public/*.html").on('change', browserSync.reload);
});
*/
"# Site-Apeperia" 
"# Site-Apeperia" 
