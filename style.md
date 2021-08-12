@import url('https://fonts.googleapis.com/css2?family=Inter&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: hsl(233, 47%, 7%);
    font-size: 15px;
    /* margin: 20vh; */
}

#main-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
}

#main-section .card {
    border-radius: 10px;
    background: hsl(244, 38%, 16%);
    width: 70vw;
    height: 60%;
    overflow: auto;
}

#main-section .card .content {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    height: 100%;
}

#main-section .card .content .info {
    width: 50%;
}

#main-section .card .content .info > div {
    padding: 50px;
}

#main-section .card .content .info > div h1 {
    font-family: 'Inter', sans-serif;
    color: hsl(0, 0%, 100%);
    font-size: 35px;
}

#main-section .card .content .info > div p {
    padding: 2rem 0 2rem;
    color: hsla(0, 0%, 100%, 0.75);
    font-family: 'Lexend Deca', sans-serif;
    font-size: 1rem;
    line-height: 1.7;
}


#main-section .card .content .img-display {
    width: 50%;
    min-height: 100%;
    background: linear-gradient(hsl(277, 64%, 61%, 50%), hsl(277, 64%, 61%, 50%)), url('/images/image-header-desktop.jpg');
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
}

.text-primary {
    color: hsl(277, 64%, 61%);
}

.stat-section .stat-headings .row {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.stat-heading {
    color: hsl(0, 0%, 100%);
    font-family: 'Inter', sans-serif;
}