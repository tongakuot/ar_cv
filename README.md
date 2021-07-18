## Alier Reng's pagedown rendered Resume

This repo contains the source-code and results of my Resume built with the [pagedown package](https://pagedown.rbind.io) and a modified version of the 'resume' template. 

The main files are:

- `areng_index.Rmd`: Source template for the cv, contains a variable `PDF_EXPORT` in the header that changes styles for pdf vs html. 
- `areng_index.html`: The final output of the template when the header variable `PDF_EXPORT` is set to `FALSE`.
- `positions.csv`: A csv with columns encoding the various fields needed for a position entry in the CV. A column `section` is also available so different sections know which rows to use.
- `css/`: Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown. (From `nstrayer/cv` & `gillsignals/cv`.)
- `parsing_functions.R`: Functions used to parse and properly format position data. (From `nstrayer/cv` & `gillsignals/cv`.)
- `strayer_template/`: Original CV and resume documents forked from `nstrayer/cv`.

## Acknowledgments

Special thanks to [Nick Strayer](http://nickstrayer.me) for providing his [pagedown CV template on GitHub](https://github.com/nstrayer/cv) and adding customization instructions. And [Amy Gill](amygill.net) for taking the time to modify Nick's CV template and making it available on GitHub for others to use.
