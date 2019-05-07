# WebCrawler
It is simple code to craw websites using Java JSoup library and download pdf.


WebCrawler and Download PDF

MiniProject - WebCrawler and download pdf file from Sites.

Work - 
1. Crawl website - done
2. Fetch url and insert in DB - done
3. Download pdf files - In progress
4. Configuration based sites/ getting input from user. - Pending
	a. website url
	b. type of file to be downloaded


Extend it fetch only specific data.

Tech Requirements 
Mysql, Java JSoup Library

Database Name - WebCrawler

Table Query - 
CREATE TABLE IF NOT EXISTS `Record` (
  `RecordID` INT(11) NOT NULL AUTO_INCREMENT,
  `URL` text NOT NULL,
  PRIMARY KEY (`RecordID`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8 AUTO_INCREMENT=1 ;





