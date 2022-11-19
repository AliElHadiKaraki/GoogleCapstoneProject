# GoogleCapstoneProject

CREATE TABLE hadi-337007.bixi_bike_project.allmonths2021 AS (
SELECT * FROM `hadi-337007.bixi_bike_project.january2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.february2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.march2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.april2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.may2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.june2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.july2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.august2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.september2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.october2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.november2021`
UNION ALL
SELECT * FROM `hadi-337007.bixi_bike_project.december2021`
);
