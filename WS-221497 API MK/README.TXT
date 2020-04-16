-- дать права для просмотра метрик согласно настройкам JDBC подключения SMP
grant select on v_$sysmetric_history to SMP_T2_RUS;