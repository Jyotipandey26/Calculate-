body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: linear-gradient(to right, #a8e6cf, #dcedc1);
}

.calculator {
    background: #222;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.2);
    text-align: center;
}

#display {
    width: 100%;
    height: 50px;
    font-size: 24px;
    text-align: right;
    padding: 10px;
    border: none;
    outline: none;
    background: #333;
    color: white;
    border-radius: 5px;
    margin-bottom: 10px;
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
}

button {
    width: 60px;
    height: 60px;
    font-size: 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    background: #444;
    color: white;
}

button.operator {
    background: #f39c12;
}

button.equal {
    background: #2ecc71;
    grid-column: span 2;
}
