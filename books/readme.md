cd /mnt/c/Development/quobject.visualstudio.com/Static-Sites-Book/my/

hugo server -D


https://learn.netlify.com/en/basics/installation/

apollo@SURFACE-BOOK> hugo help                                                                          
hugo is the main command, used to build your Hugo site.                                                 
                                                                                                        
Hugo is a Fast and Flexible Static Site Generator                                                       
built with love by spf13 and friends in Go.                                                             
                                                                                                        
Complete documentation is available at http://gohugo.io/.                                               
                                                                                                        
Usage:                                                                                                  
  hugo [flags]                                                                                          
  hugo [command]                                                                                        
                                                                                                        
Available Commands:                                                                                     
  benchmark   Benchmark Hugo by building a site a number of times.                                      
  config      Print the site configuration                                                              
  convert     Convert your content to different formats                                                 
  env         Print Hugo version and environment info                                                   
  gen         A collection of several useful generators.                                                
  help        Help about any command                                                                    
  import      Import your site from others.                                                             
  list        Listing out various types of content                                                      
  new         Create new content for your site                                                          
  server      A high performance webserver                                                              
  undraft     Undraft resets the content's draft status                                                 
  version     Print the version number of Hugo                                                          
                                                                                                        
Flags:                                                                                                  
  -b, --baseURL string             hostname (and path) to the root, e.g. http://spf13.com/              
  -D, --buildDrafts                include content marked as draft                                      
  -E, --buildExpired               include expired content                                              
  -F, --buildFuture                include content with publishdate in the future                       
      --cacheDir string            filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/    
      --canonifyURLs               if true, all relative URLs will be canonicalized using baseURL       
      --cleanDestinationDir        remove files from destination not found in static directories        
      --config string              config file (default is path/config.yaml|json|toml)                  
  -c, --contentDir string          filesystem path to content directory                                 
      --debug                      debug output                                                         
  -d, --destination string         filesystem path to write files to                                    
      --disable404                 do not render 404 page                                               
      --disableKinds stringSlice   disable different kind of pages (home, RSS etc.)                     
      --disableRSS                 do not build RSS files                                               
      --disableSitemap             do not build Sitemap file                                            
      --enableGitInfo              add Git revision, date and author info to the pages                  
      --forceSyncStatic            copy all files when static is changed.                               
  -h, --help                       help for hugo                                                        
      --i18n-warnings              print missing translations                                           
      --ignoreCache                ignores the cache directory                                          
  -l, --layoutDir string           filesystem path to layout directory                                  
      --log                        enable Logging                                                       
      --logFile string             log File path (if set, logging enabled automatically)                
      --noChmod                    don't sync permission mode of files                                  
      --noTimes                    don't sync modification time of files                                
      --pluralizeListTitles        pluralize titles in lists using inflect (default true)               
      --preserveTaxonomyNames      preserve taxonomy names as written ("Gérard Depardieu" vs "gerard-dep
ardieu")                                                                                                
      --quiet                      build in quiet mode                                                  
      --renderToMemory             render to memory (only useful for benchmark testing)                 
  -s, --source string              filesystem path to read files relative from                          
      --stepAnalysis               display memory and timing of different steps of the program          
  -t, --theme string               theme to use (located in /themes/THEMENAME/)                         
      --themesDir string           filesystem path to themes directory                                  
      --uglyURLs                   if true, use /filename.html instead of /filename/                    
  -v, --verbose                    verbose output                                                       
      --verboseLog                 verbose logging                                                      
  -w, --watch                      watch filesystem for changes and recreate as needed                  
                                                                                                        
Additional help topics:                                                                                 
  hugo check     Contains some verification checks                                                      
                                                                                                        
Use "hugo [command] --help" for more information about a command.                                       