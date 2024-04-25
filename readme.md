# Charts

In this project, we have written a program to display the chart with JavaScript

## Usage

To use the chart, we must connect to the chart.js framework, which we must use the following code to be able to use all kinds of charts and colors in it.

```javascript
const chart = document.getElementById('chart');
new Chart(chart, {
  type: 'bar',
  data: {
    labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
    datasets: [
        
    {
      label: 'Chart1',
      data: [5, 5, 10, 2, 2,2]  ,
      borderRadius: Number.MAX_VALUE,
      backgroundColor:'#bbff00'
    },
    {
      label: 'Chart2',
      data: [3, 9, 10, 0, 5,9]  ,
      borderRadius: Number.MAX_VALUE,
      
      backgroundColor:'#bb00ff'
    }
]
  },
  options: {
    scales: {
      y: {
        beginAtZero: true
      }
    },
    responsive: true
  }
});
const linechart = document.getElementById('linechart');
new Chart(linechart, {
  type: 'line',
  data: {
    labels: ['1398', '1399', '1400', '1401', '1402', '1403'],
    datasets: [
        
    {
      label: 'Line',
      data: [15000, 20000, 30000, 60000, 49000,70000]   , 
      cubicInterpolationMode: 'monotone',
      tension: 0.4,
      borderDash: [5, 5]
    } 
]
  },
  options: {
    scales: {
      y: {
        beginAtZero: true
      }
    },
    responsive: true,  
  }
});
const pie = document.getElementById('pie');
new Chart(pie, {
  type: 'pie',
  data: {
    labels: ['Dokhtar', 'Pesar', 'Mard', 'Zan'],
    datasets: [
        
    {
      label: 'pie',
      data: [2500, 2000, 200, 150]   , 
      cubicInterpolationMode: 'monotone',
      tension: 0.4 
    } 
]
  },
  options: {
    scales: {
      y: {
        beginAtZero: true
      }
    },
    responsive: true,  
  }
});
```

## Result

This project was written by Majid Tajanjari and the Aiolearn team, and we need your support!❤️

# چارت و نمودار

در این پروژه برنامه ای برای نمایش نمودار با جاوا اسکریپت نوشته ایم

## Usage

برای استفاده از نمودار باید به فریم ورک chart.js متصل شویم که باید از کد زیر استفاده کنیم تا بتوانیم از انواع نمودارها و رنگ ها در آن استفاده کنیم.

```javascript
const chart = document.getElementById('chart');
new Chart(chart, {
  type: 'bar',
  data: {
    labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
    datasets: [
        
    {
      label: 'Chart1',
      data: [5, 5, 10, 2, 2,2]  ,
      borderRadius: Number.MAX_VALUE,
      backgroundColor:'#bbff00'
    },
    {
      label: 'Chart2',
      data: [3, 9, 10, 0, 5,9]  ,
      borderRadius: Number.MAX_VALUE,
      
      backgroundColor:'#bb00ff'
    }
]
  },
  options: {
    scales: {
      y: {
        beginAtZero: true
      }
    },
    responsive: true
  }
});
const linechart = document.getElementById('linechart');
new Chart(linechart, {
  type: 'line',
  data: {
    labels: ['1398', '1399', '1400', '1401', '1402', '1403'],
    datasets: [
        
    {
      label: 'Line',
      data: [15000, 20000, 30000, 60000, 49000,70000]   , 
      cubicInterpolationMode: 'monotone',
      tension: 0.4,
      borderDash: [5, 5]
    } 
]
  },
  options: {
    scales: {
      y: {
        beginAtZero: true
      }
    },
    responsive: true,  
  }
});
const pie = document.getElementById('pie');
new Chart(pie, {
  type: 'pie',
  data: {
    labels: ['Dokhtar', 'Pesar', 'Mard', 'Zan'],
    datasets: [
        
    {
      label: 'pie',
      data: [2500, 2000, 200, 150]   , 
      cubicInterpolationMode: 'monotone',
      tension: 0.4 
    } 
]
  },
  options: {
    scales: {
      y: {
        beginAtZero: true
      }
    },
    responsive: true,  
  }
});
```

## نتیجه

این پروژه توسط مجید تجن جاری و تیم Aiolearn نوشته شده است و ما به حمایت شما نیازمندیم!❤️