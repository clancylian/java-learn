# java-learn

## PGSQL创建自增ID
DROP SEQUENCE if EXISTS "public"."seq_config_server_properties";  
CREATE SEQUENCE "public"."seq_config_server_properties"  
INCREMENT 1  
MINVALUE 1  
MAXVALUE 9223372036854775807  
START 1  
CACHE 1;
