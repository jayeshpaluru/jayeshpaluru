# Hey there! I'm Jayesh Paluru 👋

### I'm a Data Science student at the University of Texas at Dallas (UTD) and a Google and IBM certified data analyst. I am passionate about data science, web development, and AI.

## Education 🎓
### Honors Bachelor of Sciences in Data Science at The University of Texas at Dallas
### IBM Data Analytics Professional Certification – IBM Skills Network
### Google Data Analytics Professional Certification – Google Career Certificates

## Technical Skills 🛠️
### Data Analysis: Excel, SQL, Python, R, NumPy, Pandas, Sci-kit Learn, Matplotlib, Seaborn
### Data Visualization: PowerBI, Tableau, Matplotlib, Seaborn
### Machine Learning: PyTorch, Keras, TensorFlow, Sci-kit Learn
### Web Development: HTML, CSS, JavaScript, jQuery, Bootstrap, Node.js
### Tools: MS SQL Server, MySQL, Git, Microsoft Suite, Google Suite

## Statistics 📊
<div style="display:flex;justify-content:space-around;align-items:center;">
    <div>
        <h3>Projects Completed</h3>
        <p>100+</p>
    </div>
    <div>
        <h3>Lines of Code Written</h3>
        <p>10,000+</p>
    </div>
    <div>
        <h3>GitHub Followers</h3>
        <p>500+</p>
    </div>
</div>

## Personal Website 🌐
### Check out my personal website [here](https://www.jayeshp.com/) to learn more about me!

## Skills & Interests 🤹‍♂️
### Data Analysis, Data Visualization, Data Science, Machine Learning, Web Development, Communication, Leadership
### I love swimming, watching tv, and reading! 🏊📺📚

<script src="https://cdn.jsdelivr.net/npm/apexcharts"></script>
<div id="chart"></div>
<script>
    var options = {
        series: [{
            name: 'Data Analysis',
            data: [70, 80, 90, 85, 70, 65, 80, 85, 90]
        }, {
            name: 'Machine Learning',
            data: [60, 70, 80, 75, 60, 55, 70, 75, 80]
        }, {
            name: 'Web Development',
            data: [50, 60, 70, 65, 50, 45, 60, 65, 70]
        }],
        chart: {
            height: 350,
            type: 'line',
            zoom: {
                enabled: false
            }
        },
        dataLabels: {
            enabled: false
        },
        stroke: {
            width: [5, 5, 5],
            curve: 'straight'
        },
        title: {
            text: 'Skills Proficiency Chart',
            align: 'center',
            style: {
                fontSize: '24px'
            }
        },
        legend: {
            tooltipHoverFormatter: function(val, opts) {
                return val + ' - ' + opts.w.globals.series[opts.seriesIndex][opts.dataPointIndex] + '%'
            }
        },
        markers:     {
        size: 7,
        strokeWidth: 0,
        colors: ['#008FFB', '#00E396', '#FEB019', '#FF4560', '#775DD0', '#546E7A', '#26a69a', '#D10CE8', '#DCDCDC'],
        hover: {
            sizeOffset: 7
        }
    },
    xaxis: {
        categories: ['Python', 'R', 'SQL', 'Excel', 'NumPy', 'Pandas', 'Sci-kit Learn', 'Matplotlib', 'Seaborn'],
    },
    tooltip: {
        y: [
            {
                title: {
                    formatter: function (val) {
                        return val + " %"
                    }
                }
            },
            {
                title: {
                    formatter: function (val) {
                        return val + " %"
                    }
                }
            },
            {
                title: {
                    formatter: function (val) {
                        return val + " %"
                    }
                }
            }
        ]
    }
};

var chart = new ApexCharts(document.querySelector("#chart"), options);
chart.render();
</script>
