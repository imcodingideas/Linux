# Plex Meta Manager (PMM)

This contains all my PMM scripts. It contains 3 YAML files:

 1. *config.yml* -  my plex and imdb connection strings
 2. *movies.yml* -  my custom smart Movies collection filters
 3. *shows.yml* -  my custom smart TV Show collection filters

To manually run the script, run the following commands in the terminal: 

     docker exec -it plex-meta-manager bash
     python plex_meta_manager.py -r

**Note**: I need to create a *music.yml* and create custom smart Music collection filters.
