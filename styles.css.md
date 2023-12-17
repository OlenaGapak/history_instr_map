body {
    font-family: 'Arial', sans-serif;
    margin: 0;
}

.container {
    display: flex;
}

.filter-column {
    width: 30%;
    background-color: #f1f1f1;
    padding: 20px;
}

.main-content {
    flex-grow: 1;
    padding: 20px;
}

.dropdown-btn {
    display: block;
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    text-align: left;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #fff;
    box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    z-index: 1;
}

.dropdown-content a {
    display: block;
    padding: 10px;
    text-decoration: none;
    color: #333;
}

.dropdown-content a:hover {
    background-color: #f1f1f1;
}

.tooltip {
    position: relative;
    display: inline-block;
    margin-left: 5px;
}

.tooltip:before {
    content: '?';
    display: inline-block;
    width: 20px;
    height: 20px;
    background-color: #ccc;
    color: #fff;
    text-align: center;
    border-radius: 50%;
    cursor: pointer;
}

.tooltip:hover + .dropdown-content {
    display: block;
}
