CREATE VIEW 우수고객(고객아이디, 고객이름, 나이)

AS SELECT 고객아이디, 고객이름, 나이

       FROM 고객
       WHERE 등급=VIP

WITH CHECK OPTION;
워우워