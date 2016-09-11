Install :

	npm install

	./start



DDL table oracle :

CREATE TABLE users( 
	id NUMBER NOT NULL,
  	username VARCHAR(50) NOT NULL,
  	password VARCHAR(80),
  	akses VARCHAR(15),
  	CONSTRAINT users_pk PRIMARY KEY (id)
);

CREATE SEQUENCE users_seq START WITH 1 INCREMENT BY 1;

CREATE OR REPLACE TRIGGER users_trigger
BEFORE INSERT ON users
REFERENCING NEW AS NEW
FOR EACH ROW
BEGIN
SELECT users_seq.nextval INTO :NEW.ID FROM dual;
END;

select * from ais_position_report where tanggal between to_date('2016-3-1','YYYY-MM-DD') and to_date('2016-3-31','YYYY-MM-DD');

position:fixed;bottom:0;top:0;padding:20px 0 0 0;overflow:scroll;

ZPPI
	{"msg":"ok","zppi":[{"LOCATION_ID":"27","ITEM_NO":"0","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.516","LATITUDE":"-13.383","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"11","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"135.920","LATITUDE":"-11.415","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"2","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.664","LATITUDE":"-13.193","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"3","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.687","LATITUDE":"-13.353","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"4","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.751","LATITUDE":"-13.197","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"5","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.756","LATITUDE":"-13.741","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"6","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.767","LATITUDE":"-13.880","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"7","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.831","LATITUDE":"-13.327","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"8","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.858","LATITUDE":"-13.264","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"9","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.993","LATITUDE":"-13.299","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"10","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"126.027","LATITUDE":"-13.369","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"11","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"126.421","LATITUDE":"-13.218","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"12","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"126.423","LATITUDE":"-13.284","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"13","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"126.531","LATITUDE":"-13.432","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"14","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"126.563","LATITUDE":"-13.338","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"0","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"128.663","LATITUDE":"-13.623","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"1","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"128.714","LATITUDE":"-13.733","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"2","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"128.740","LATITUDE":"-13.572","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"3","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"128.898","LATITUDE":"-13.561","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"4","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"128.951","LATITUDE":"-13.484","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"5","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"128.967","LATITUDE":"-13.476","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"6","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.006","LATITUDE":"-13.506","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"7","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.172","LATITUDE":"-13.403","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"8","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.271","LATITUDE":"-13.290","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"9","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.341","LATITUDE":"-13.299","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"10","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.425","LATITUDE":"-13.121","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"11","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.641","LATITUDE":"-12.984","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"12","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.695","LATITUDE":"-12.900","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"13","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.841","LATITUDE":"-12.898","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"14","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.953","LATITUDE":"-11.521","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"15","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"129.958","LATITUDE":"-11.372","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"16","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"130.030","LATITUDE":"-11.200","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"17","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"130.082","LATITUDE":"-11.253","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"18","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"130.097","LATITUDE":"-11.110","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"19","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"133.665","LATITUDE":"-11.220","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"20","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"133.760","LATITUDE":"-11.418","CLOSEE":"6"},{"LOCATION_ID":"28","ITEM_NO":"21","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"133.917","LATITUDE":"-11.616","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"0","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"134.069","LATITUDE":"-11.568","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"1","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"134.185","LATITUDE":"-11.469","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"2","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"134.236","LATITUDE":"-11.559","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"3","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"134.332","LATITUDE":"-11.475","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"4","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"134.513","LATITUDE":"-11.481","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"5","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"134.858","LATITUDE":"-11.058","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"6","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"134.953","LATITUDE":"-11.103","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"7","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"135.226","LATITUDE":"-11.452","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"8","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"135.331","LATITUDE":"-11.473","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"9","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"135.445","LATITUDE":"-11.654","CLOSEE":"6"},{"LOCATION_ID":"3","ITEM_NO":"10","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"135.792","LATITUDE":"-11.537","CLOSEE":"6"},{"LOCATION_ID":"27","ITEM_NO":"1","TANGGAL":"2016-07-19 00:00:00","LONGITUDE":"125.648","LATITUDE":"-13.428","CLOSEE":"6"}],"tanggal":"19-07-2016","q":"select LOCATION_ID,ITEM_NO,TANGGAL,LONGITUDE,LATITUDE,(TO_DATE('2016-07-25','YYYY-MM-DD')-TANGGAL) CLOSEE from ZPPI where (TO_DATE('2016-07-25','YYYY-MM-DD')-TANGGAL)<=(select min((TO_DATE('2016-07-25','YYYY-MM-DD')-TANGGAL)) from zppi) order by CLOSEE asc"}


KAPAL
	{"msg":"ok","kapal":[
		{"MMSI":"538005038","TG":"2016-06-11 07:13:27","TMP":"5","TGL2":"2016-06-11 00:00:00","HR":"07","LONGITUDE":"142.63692","LATITUDE":"3.22654"},
		{"MMSI":"354161000","TG":"2016-06-11 07:14:01","TMP":"39","TGL2":"2016-06-11 00:00:00","HR":"07","LONGITUDE":"134.59889","LATITUDE":"1.23754"},
		{"MMSI":"406924568","TG":"2016-06-11 07:13:41","TMP":"18","TGL2":"2016-06-11 00:00:00","HR":"07","LONGITUDE":"135.49379","LATITUDE":"5.35653"},
		{"MMSI":"588000006","TG":"2016-06-11 07:12:32","TMP":"0","TGL2":"2016-06-11 00:00:00","HR":"07","LONGITUDE":"133.24287","LATITUDE":"0"},
		{"MMSI":"636091017","TG":"2016-06-11 07:08:00","TMP":"0","TGL2":"2016-06-11 00:00:00","HR":"07","LONGITUDE":"122.43918","LATITUDE":"6.7984"},
		{"MMSI":"553111734","TG":"2016-06-11 07:18:11","TMP":"0","TGL2":"2016-06-11 00:00:00","HR":"07","LONGITUDE":"125.61067","LATITUDE":"0"}
	],
	"tanggal":"11-06-2016",
	"jam":7,
	"q":"select a.*,b.LONGITUDE,B.LATITUDE from (select MMSI,max(TANGGAL) TG ,max(\"TIMESTAMP\") TMP, trunc(TANGGAL) TGL2, to_char(TANGGAL,'HH24') HR\n    from AIS_POSITION_REPORT_IND2 \n    group by MMSI,trunc(TANGGAL),to_char(TANGGAL,'HH24')\n    having trunc(TANGGAL)=to_date('11-06-2016','DD-MM-YYYY') and  to_char(TANGGAL,'HH24') = 7) a\n    left join AIS_POSITION_REPORT_IND2 b on a.MMSI=b.MMSI and a.tg=b.TANGGAL and a.TMP=b.\"TIMESTAMP\" \n    left join AIS_SHIP c on b.MMSI=c.MMSI\n    where c.TYPE=36 and  b.longitude > 95 and b.longitude < 145 and b.latitude>-9 and b.latitude<10 and LAND=0\n    FETCH FIRST 500 ROWS ONLY"}