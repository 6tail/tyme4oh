## 公历转农历示例

    // install
    ohpm install tyme4oh
     
    // import
    import {SolarDay} from 'tyme4oh';
     
    const solar = SolarDay.fromYmd(1986, 5, 29);
     
    // 1986年5月29日
    console.log(solar.toString());
    
    // 农历丙寅年四月廿一
    console.log(solar.getLunarDay().toString());
