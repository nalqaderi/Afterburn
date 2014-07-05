Afterburn
=========

# Rotten Tomatoes Project


movie = Rotten Tomatoes::lucky get movie info movie_name
#get a movie
puts movie.title
# what movie you were thinking about watching
puts "Released in #{movie.year
#when the movie was released
puts "#{movie.runtime} long
#how long the movie was
puts "Rated #{movie.rating}"
# what the movie was rated
puts "Average critic rating of #{movie.tomatometer_average_rating
# average critic rating 
puts "#{movie.tomatometer_reviews_counted} reviews taken into consideration."
#which reviews were counted and looked about
puts "#{movie.tomatometer_fresh} critic/s said it was fresh."
# which critics said it was a "fresh" (good) movie
puts "#{movie.tomatometer_rotten} critic/s said it was rotten
# which critic said it wasn't such a good movie
puts "Audience rating of #{movie.audience_rating}% fresh."
# what the audience thought about it
puts "Average audience rating of #{movie.audience_average_rating}."
# same as aboce
puts "#{movie.audience_number_of_ratings} audience ratings."
# number of audience ratings
puts "Released #{movie.release}"
# when movie was released
puts "Distributed by #{movie.distributor}"
# who released the movie
movie.genres.each do |genre|
  puts "In the #{genre} genre."
# what genre 


