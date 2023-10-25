Questions Easy:
a)  -346 Albums, from my terminal, when I seed it.
    -It's Eric Clapton
    -The tracks with a duration of 188133 ms is 'Perfect'
    -Guns N Roses

b)  - There are 13 Album where the word 'Great' is in
    - 4 Albums deleted
    -2 Album From AC/DC
    -0 tracks with a duration  of 158589milisec
c)  -   acdc_songs = Track.where(artist: "AC/DC")
           acdc_songs.each do |song|
              puts song.title
          end
    -   album_songs = Track.where(album: "Let There Be Rock")
            album_songs.each do |song|
              puts song.title
          end
    -   album_songs = Track.where(album: "Let There Be Rock")
          total_price = 0.0
          album_songs.each do |song|
          total_price += song.price
        end
        puts "Total album cost is #{total_price} euros."
    -   deep_purple_songs = Track.where(artist: "Deep Purple")
          total_cost = 0.0
          deep_purple_songs.each do |song|
          total_cost += song.price
        end
        puts "The total discographia cost #{total_cost} euros."
    - eric_clapton_songs = Track.where(artist: "Eric Clapton")
        eric_clapton_songs.each do |song|
        song.update(artist: "Britney Spears")
      end

    
