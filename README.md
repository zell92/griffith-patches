# griffith-patches

# Patches information

The directory named "lib" contains 2 patches for the "Griffith" program.
In particular, two files have been modified:
* Movie.py -> This patch allows the use of the program, even if the "griffith.cc" server is offline.
* PluginMovieMyMoviesIt.py -> This patch allows you to extract all the data about a movie (including the poster) from mymovies.cit. It is also easier to be able to identify a movie in search results.

# How to install

1. Install Griffith
2. Go to the "lib" folder (..\Griffith\lib): for example E:\Program Files (x86)\Griffith\lib
3. Copy the movie.py file inside the folder
* If you are asked to replace the file, answer yes
4. Go to the "movie" folder (..\Griffith\lib\plugins\movie): for example E:\Program Files (x86)\Griffith\lib\plugins\movie
5. Copy the PluginMovieMyMoviesIt.py file inside the folder
* If you are asked to replace the file, answer yes

to see all branch go to https://github.com/zell92/Griffith-mirror/tree/patch-2

Thanks to the creators of this wonderful program, which you can find here: https://github.com/FiloSottile/Griffith-mirror