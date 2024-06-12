### typora——test
增删改查
INSERT INTO `student`(`id`, `name`, `grade`) VALUES (null,'张三','男')
DELETE FROM `student` WHERE id = 2
UPDATE `student` SET `name`='张三','grade'='男' WHERE id =2
SELECT * FROM `student` WHERE id = 2