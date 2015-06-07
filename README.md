CREATE TABLE `tbl_courses` (
  `crs_id` int(11) NOT NULL AUTO_INCREMENT,
  `crs_code` varchar(6) NOT NULL,
  `crs_name` varchar(30) NOT NULL,
  `crs_description` varchar(250) DEFAULT NULL,
  `crs_type` varchar(8) NOT NULL,
  `crs_nb_credits` int(11) NOT NULL,
  `crs_lab` varchar(3) NOT NULL,
  PRIMARY KEY (`crs_id`));
