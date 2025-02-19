# Intro to the Louisville Data Commons project 
[About Text (about page)]

[Bylaws]

[How We Made This]

[About Text (about page)]: https://docs.google.com/document/d/1wq73t1mLUfFTjMU8arMe8oFwhct2Ei0teWmndlPB7r0/edit?usp=sharing
[Bylaws]: https://docs.google.com/document/d/12FSVXbFbkdq1ydorAyfewKHysIXSmrpAz4UpmvxJ9XI/edit?usp=sharing
[How We Made This]: https://docs.google.com/document/d/15AnzQm2cPlVUfLqsx55BvhemsvGO8kZXMTLs7JId3Ac/edit?usp=sharing

# CKAN Resources

[CKAN user guide]

[Maintaining CKAN]

[CKAN GIT Repo]

[CKAN GIT Repo]: https://github.com/ckan/ckan.git

[CKAN user guide]: https://docs.ckan.org/en/ckan-2.7.3/user-guide.html

[Maintaining CKAN]: https://docs.ckan.org/en/ckan-2.7.3/maintaining/index.html

[SSL and CKAN]: https://github.com/conwetlab/ckanext-oauth2/wiki/Starting-CKAN-over-HTTPs-using-Nginx

Config file: ``/etc/ckan/default/production.ini``

Error log file: ``tail -f  /var/log/httpd/ckan_error.log``

Update Permissions for cert file: chmod 400 (Drag File  here)

Public File Path:  ``/usr/lib/ckan/default/src/ckan/ckan/public/base/images``

[CKAN andino theme]

[CKAN andino theme]: https://github.com/datosgobar/portal-andino-theme

# NGINX commands

Restarting: ``sudo service nginx reload``

# Ways to integrate CKAN with Wordpress

All pages but data are on a wordpress site and the data is a separate CKAN site:

See: [Post 1] & [Post 2] & [Slides]

Sites: [York Open Data Site] & [Data.gov] & [Western Pennsylvania Regional Data Center]

Wordpress & CKAN Integration Extensions: [Extensions]

Wordpress Command Line Interface: [CLI]

[York Open Data Site]: https://www.yorkopendata.org
[Post 1]: https://www.yorkopendata.org/ckan-and-wordpress-integration-blog-by-castlegate-it/
[Post 2]: https://www.castlegateit.co.uk/2015/03/ckan-and-wordpress-integration/
[Slides]: https://metaodi.ch/posts/2016/10/how-we-combined-wordpress-with-ckan/
[Data.gov]: https://www.data.gov
[Extensions]: https://extensions.ckan.org
[CLI]: https://wp-cli.org
[Western Pennsylvania Regional Data Center]: https://www.wprdc.org

# Vagrant resources

``vagrant up``

``vagrant provision``

``vagrant ssh``

``/usr/lib/ckan/src/ckan``


