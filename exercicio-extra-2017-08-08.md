# apache
# histórico de versões apache http server
# 1.3	
# 2.0	 -> https://svn.apache.org/viewvc/httpd/httpd/branches/2.0.x/CHANGES?view=markup
# 2.2	 -> https://svn.apache.org/viewvc/httpd/httpd/branches/2.2.x/CHANGES?view=markup
# 2.4	 -> https://svn.apache.org/viewvc/httpd/httpd/branches/2.4.x/CHANGES?view=markup
#
# nginx
# 
# Changes with nginx 1.13.4                                        08 Aug 2017
#
#   *) Feature: the ngx_http_mirror_module.
#
#    *) Bugfix: client connections might be dropped during configuration
#       testing when using the "reuseport" parameter of the "listen"
#       directive on Linux.
#
#    *) Bugfix: request body might not be available in subrequests if it was
#       saved to a file and proxying was used.
#
#    *) Bugfix: cleaning cache based on the "max_size" parameter did not work
#       on Windows.
#
#    *) Bugfix: any shared memory allocation required 4096 bytes on Windows.
#
#    *) Bugfix: nginx worker might be terminated abnormally when using the
#      "zone" directive inside the "upstream" block on Windows.
#
#
# Changes with nginx 1.13.3                                        11 Jul 2017
#
 #   *) Security: a specially crafted request might result in an integer
  #     overflow and incorrect processing of ranges in the range filter,
   #    potentially resulting in sensitive information leak (CVE-2017-7529).
#
#
# Changes with nginx 1.13.2                                        27 Jun 2017

 #   *) Change: nginx now returns 200 instead of 416 when a range starting
  #     with 0 is requested from an empty file.
#
#    *) Feature: the "add_trailer" directive.
 #      Thanks to Piotr Sikora.
#
 #   *) Bugfix: nginx could not be built on Cygwin and NetBSD; the bug had
  #     appeared in 1.13.0.

   # *) Bugfix: nginx could not be built under MSYS2 / MinGW 64-bit.
      # Thanks to Orgad Shaneh.

    # *) Bugfix: a segmentation fault might occur in a worker process when
       # using SSI with many includes and proxy_pass with variables.

    # *) Bugfix: in the ngx_http_v2_module.
      # Thanks to Piotr Sikora.


# Changes with nginx 1.13.1                                        30 May 2017

 #   *) Feature: now a hostname can be used as the "set_real_ip_from"
  #     directive parameter.

   # *) Feature: vim syntax highlighting scripts improvements.

    # *) Feature: the "worker_cpu_affinity" directive now works on DragonFly
     #  BSD.
      # Thanks to Sepherosa Ziehau.

    # *) Bugfix: SSL renegotiation on backend connections did not work when
       # using OpenSSL before 1.1.0.

    # *) Workaround: nginx could not be built with Oracle Developer Studio
     #  12.5.

    # *) Workaround: now cache manager ignores long locked cache entries when
     #  cleaning cache based on the "max_size" parameter.

   # *) Bugfix: client SSL connections were immediately closed if deferred
    #   accept and the "proxy_protocol" parameter of the "listen" directive
     #  were used.

    # *) Bugfix: in the "proxy_cache_background_update" directive.

    # *) Workaround: now the "tcp_nodelay" directive sets the TCP_NODELAY
     #  option before an SSL handshake.


# Changes with nginx 1.13.0                                        25 Apr 2017

 #   *) Change: SSL renegotiation is now allowed on backend connections.

  #  *) Feature: the "rcvbuf" and "sndbuf" parameters of the "listen"
   #    directives of the mail proxy and stream modules.

    # *) Feature: the "return" and "error_page" directives can now be used to
     #  return 308 redirections.
      # Thanks to Simon Leblanc.

    # *) Feature: the "TLSv1.3" parameter of the "ssl_protocols" directive.

    # *) Feature: when logging signals nginx now logs PID of the process which
       sent the signal.

#    *) Bugfix: in memory allocation error handling.

 #   *) Bugfix: if a server in the stream module listened on a wildcard
  #     address, the source address of a response UDP datagram could differ
   #    from the original datagram destination address.
   
# Wordpress
# August 2, 2017	WordPress 4.8.1 Maintenance Release -> https://wordpress.org/news/2017/06/evans/
# June 8, 2017	WordPress 4.8 “Evans” -> https://wordpress.org/news/2017/08/wordpress-4-8-1-maintenance-release/
# June 1, 2017	WordPress 4.8 Release Candidate 2 -> https://wordpress.org/news/2017/06/wordpress-4-8-release-candidate-2/
# May 25, 2017	WordPress 4.8 Release Candidate
# May 23, 2017	WordPress 4.8 Beta 2
# May 16, 2017	WordPress 4.7.5 Security and Maintenance Release
# May 13, 2017	WordPress 4.8 Beta 1
# April 20, 2017	WordPress 4.7.4 Maintenance Release
# March 6, 2017	WordPress 4.7.3 Security and Maintenance Release
# January 26, 2017	WordPress 4.7.2 Security Release
# January 11, 2017	WordPress 4.7.1 Security and Maintenance Release
# December 6, 2016	WordPress 4.7 “Vaughan”
# November 24, 2016	WordPress 4.7 Release Candidate
# November 16, 2016	WordPress 4.7 Beta 4
# November 11, 2016	WordPress 4.7 Beta 3
# November 4, 2016	WordPress 4.7 Beta 2
# October 28, 2016	WordPress 4.7 Beta 1
# September 7, 2016	WordPress 4.6.1 Security and Maintenance Release
# August 16, 2016	WordPress 4.6 “Pepper”
# August 11, 2016	WordPress 4.6 RC2
# July 27, 2016	WordPress 4.6 Release Candidate
July 20, 2016	WordPress 4.6 Beta 4
July 13, 2016	WordPress 4.6 Beta 3
July 6, 2016	WordPress 4.6 Beta 2
June 30, 2016	WordPress 4.6 Beta 1
June 18, 2016	WordPress 4.5.3 Maintenance and Security Release
May 6, 2016	WordPress 4.5.2 Security Release
April 26, 2016	WordPress 4.5.1 Maintenance Release
April 12, 2016	WordPress 4.5 “Coleman”
April 10, 2016	WordPress 4.5 RC2
March 24, 2016	WordPress 4.5 Release Candidate
March 17, 2016	WordPress 4.5 Beta 4
March 10, 2016	WordPress 4.5 Beta 3
March 3, 2016	WordPress 4.5 Beta 2
February 25, 2016	WordPress 4.5 Beta 1
February 2, 2016	WordPress 4.4.2 Security and Maintenance Release
January 6, 2016	WordPress 4.4.1 Security and Maintenance Release
December 8, 2015	WordPress 4.4 “Clifford”
November 25, 2015	WordPress 4.4 Release Candidate
November 12, 2015	WordPress 4.4 Beta 4
November 4, 2015	WordPress 4.4 Beta 3
October 28, 2015	WordPress 4.4 Beta 2
October 22, 2015	WordPress 4.4 Beta 1
September 15, 2015	WordPress 4.3.1 Security and Maintenance Release
August 18, 2015	WordPress 4.3 “Billie”
August 4, 2015	WordPress 4.2.4 Security and Maintenance Release
July 29, 2015	WordPress 4.3 Release Candidate
July 23, 2015	WordPress 4.2.3 Security and Maintenance Release
July 22, 2015	WordPress 4.3 Beta 4
July 15, 2015	WordPress 4.3 Beta 3
July 8, 2015	WordPress 4.3 Beta 2
July 2, 2015	WordPress 4.3 Beta 1
May 7, 2015	WordPress 4.2.2 Security and Maintenance Release
April 27, 2015	WordPress 4.2.1 Security Release
April 23, 2015	WordPress 4.2 “Powell”
April 21, 2015	WordPress 4.1.2 Security Release
April 15, 2015	WordPress 4.2 Release Candidate
April 3, 2015	WordPress 4.2 Beta 4
March 26, 2015	WordPress 4.2 Beta 3
March 19, 2015	WordPress 4.2 Beta 2
March 12, 2015	WordPress 4.2 Beta 1
February 18, 2015	WordPress 4.1.1 Maintenance Release
December 18, 2014	WordPress 4.1 “Dinah”
WordPress 4.1 Release Candidate 3
December 11, 2014	WordPress 4.1 Release Candidate
November 20, 2014	WordPress 4.0.1 Security Release
November 14, 2014	WordPress 4.1 Beta 1
September 4, 2014	WordPress 4.0 “Benny”
August 27, 2014	WordPress 4.0 Release Candidate
August 15, 2014	WordPress 4.0 Beta 4
August 6, 2014	WordPress 3.9.2 Security Release
July 18, 2014	WordPress 4.0 Beta 2
July 10, 2014	WordPress 4.0 Beta 1
May 8, 2014	WordPress 3.9.1 Maintenance Release
April 16, 2014	WordPress 3.9 “Smith”
April 15, 2014	WordPress 3.9 Release Candidate 2
April 14, 2014	WordPress 3.8.3 Maintenance Release
April 8, 2014	WordPress 3.9 Release Candidate
WordPress 3.8.2 Security Release
March 29, 2014	WordPress 3.9 Beta 3
March 20, 2014	WordPress 3.9 Beta 2
March 11, 2014	WordPress 3.9 Beta 1
January 23, 2014	WordPress 3.8.1 Maintenance Release
December 12, 2013	WordPress 3.8 “Parker”
December 10, 2013	3.8 RC2
December 4, 2013	WordPress 3.8 RC1
November 21, 2013	WordPress 3.8 Beta 1
October 29, 2013	WordPress 3.7.1 Maintenance Release
October 24, 2013	WordPress 3.7 “Basie”
October 23, 2013	WordPress 3.7 Release Candidate 2
October 18, 2013	WordPress 3.7 Release Candidate
October 10, 2013	WordPress 3.7 Beta 2
September 28, 2013	WordPress 3.7 Beta 1
September 11, 2013	WordPress 3.6.1 Maintenance and Security Release
August 1, 2013	WordPress 3.6 “Oscar”
June 21, 2013	WordPress 3.5.2 Maintenance and Security Release
April 4, 2013	WordPress 3.6 Beta 1
January 24, 2013	WordPress 3.5.1 Maintenance and Security Release
December 11, 2012	WordPress 3.5 “Elvin”
November 13, 2012	WordPress 3.5 Beta 3
October 13, 2012	WordPress 3.5 Beta 2
September 27, 2012	WordPress 3.5 Beta 1 (and a bonus!)
September 6, 2012	WordPress 3.4.2 Maintenance and Security Release
June 27, 2012	WordPress 3.4.1 Maintenance and Security Release
June 13, 2012	WordPress 3.4 “Green”
June 7, 2012	WordPress 3.4 Release Candidate 2
May 27, 2012	WordPress 3.4 Release Candidate
May 3, 2012	WordPress 3.4 Beta 4
April 20, 2012	WordPress 3.3.2 (and WordPress 3.4 Beta 3)
April 12, 2012	WordPress 3.4 Beta 2
April 5, 2012	WordPress 3.4 Beta 1
January 3, 2012	WordPress 3.3.1 Security and Maintenance Release
December 12, 2011	WordPress 3.3 “Sonny”
December 11, 2011	WordPress 3.3 Release Candidate 3
December 7, 2011	WordPress 3.3 Release Candidate 2
December 1, 2011	WordPress 3.3 Release Candidate 1
November 24, 2011	WordPress 3.3 Beta 4 Available Now
November 8, 2011	WordPress 3.3 Beta 3 Available
October 20, 2011	WordPress 3.3 Beta 2
October 11, 2011	WordPress 3.3 Beta 1
July 12, 2011	WordPress 3.2.1
July 4, 2011	WordPress 3.2 now available
June 29, 2011	WordPress 3.1.4 (and 3.2 Release Candidate 3)
June 14, 2011	WordPress 3.2 Release Candidate
May 25, 2011	WordPress 3.1.3 (and WordPress 3.2 Beta 2)
May 12, 2011	WordPress 3.2, Beta 1
April 26, 2011	WordPress 3.1.2
April 5, 2011	WordPress 3.1.1
February 23, 2011	WordPress 3.1, lots of fun
February 7, 2011	WordPress 3.0.5 (and 3.1 Release Candidate 4)
January 22, 2011	WordPress 3.1 Release Candidate 3
January 1, 2011	WordPress 3.1 Release Candidate 2
December 29, 2010	3.0.4 Important Security Update
December 25, 2010	WordPress 3.1 Release Candidate
December 15, 2010	WordPress 3.1 Beta 2
December 8, 2010	WordPress 3.0.3
November 30, 2010	WordPress 3.0.2
November 25, 2010	WordPress 3.1 Beta 1
Android Update: 1.3.8
September 30, 2010	WordPress for iPhone/iPad v2.6 Released
July 29, 2010	WordPress 3.0.1
June 17, 2010	WordPress 3.0 "Thelonious"
February 15, 2010	WordPress 2.9.2
January 4, 2010	WordPress 2.9.1
December 19, 2009	WordPress 2.9, oh so fine
November 12, 2009	WordPress 2.8.6 Security Release
October 20, 2009	WordPress 2.8.5: Hardening Release
August 12, 2009	WordPress 2.8.4: Security Release
August 3, 2009	WordPress 2.8.3 Security Release
July 20, 2009	WordPress 2.8.2
July 9, 2009	WordPress 2.8.1
June 11, 2009	2.8 Release Jazzes Themes and Widgets
February 10, 2009	WordPress 2.7.1
December 11, 2008	WordPress 2.7 "Coltrane"
October 23, 2008	WordPress 2.6.3
September 8, 2008	WordPress 2.6.2
August 15, 2008	WordPress 2.6.1
July 15, 2008	WordPress 2.6
April 25, 2008	WordPress 2.5.1
March 29, 2008	WordPress 2.5
December 29, 2007	WordPress 2.3.2
October 26, 2007	WordPress 2.3.1
October 24, 2007	WordPress 2.3.1 Release Candidate 1
September 25, 2007	WordPress 2.3
September 19, 2007	WordPress 2.3 Release Candidate 1
September 11, 2007	WordPress 2.3 Beta 3
September 8, 2007	WordPress 2.2.3
August 5, 2007	WordPress 2.2.2 and 2.0.11
June 21, 2007	WordPress 2.2.1
May 16, 2007	WordPress 2.2
April 3, 2007	WordPress 2.1.3 and 2.0.10
March 2, 2007	WordPress 2.1.1 dangerous, Upgrade to 2.1.2
February 21, 2007	New Releases: 2.1.1 and 2.0.9
January 22, 2007	WordPress 2.1 Ella
January 15, 2007	WordPress 2.0.7
January 5, 2007	WordPress 2.0.6
October 27, 2006	WordPress 2.0.5 – Ronan
October 23, 2006	MU 1.0 and bbPress
July 29, 2006	WordPress 2.0.4
June 1, 2006	WordPress 2.0.3
April 1, 2006	WordPattern (April Fools!)
March 10, 2006	2.0.2 Security Release
January 31, 2006	2.0.1 Release
December 31, 2005	WordPress 2
December 20, 2005	2.0 Release Candidate
August 14, 2005	WordPress 1.5.2
June 29, 2005	WordPress 1.5.1.3 Available
May 9, 2005	WordPress 1.5.1 (Updated)
February 17, 2005	Announcing WordPress 1.5
December 15, 2004	WordPress 1.2.2
October 6, 2004	WordPress 1.2.1
May 22, 2004	WordPress 1.2
May 20, 2004	Final Release Candidate
May 14, 2004	1.2 Release Candidate
May 11, 2004	WordPress in Gentoo
April 29, 2004	1.2 Beta
March 22, 2004	Download Link Fixed
March 11, 2004	WordPress updates
January 25, 2004	1.0.1 "Miles" Release Available
January 15, 2004	1.0.1 Release Candidate
January 3, 2004	WordPress 1.0
October 11, 2003	0.72 Final Version Available
October 4, 2003	0.72 Release Candidate 1
September 1, 2003	Point 72 Beta 2 Available
August 24, 2003	Point 72 Beta 1 Available
July 31, 2003	Link Manager Changes
June 25, 2003	WordPress Version 0.711 Now Available
June 9, 2003	WordPress 0.71 Now Available
.71 Beta 3
June 6, 2003	.71 Beta
May 27, 2003	WordPress Now Available
May 25, 2003	New Point Seven Beta
