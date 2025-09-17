    body {
        background-color: black;
        color: white;
        font-family: 'Roboto', sans-serif;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        overflow: hidden;
    }

    .screen {
        display: none;
        width: 100%;
        height: 100vh;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding: 20px;
    }

    .screen.active {
        display: flex;
    }

    .main-title {
        font-family: 'Dancing Script', cursive;
        font-size: 4rem;
        font-weight: 700;
        color: white;
        margin-bottom: 20px;
        text-shadow: 2px 2px 4px rgba(255,255,255,0.1);
    }

    .subtitle {
        font-family: 'Dancing Script', cursive;
        font-size: 1.8rem;
        color: white;
        margin-bottom: 60px;
        opacity: 0.9;
    }

    .button-container {
        display: flex;
        gap: 40px;
        margin-top: 40px;
    }

    .choice-button {
        background-color: white;
        color: black;
        font-family: 'Caveat', cursive;
        font-size: 2rem;
        font-weight: 700;
        padding: 20px 60px;
        border: none;
        border-radius: 50px;
        cursor: pointer;
        transition: all 0.3s ease;
        box-shadow: 0 4px 15px rgba(255,255,255,0.3);
    }

    .choice-button:hover {
        transform: translateY(-3px);
        box-shadow: 0 6px 20px rgba(255,255,255,0.4);
        background-color: #f0f0f0;
    }

    .message-text {
        font-family: 'Roboto', sans-serif;
        font-size: 1.5rem;
        color: white;
        line-height: 1.8;
        max-width: 800px;
        margin-bottom: 60px;
        font-weight: 300;
    }

    .next-button {
        background-color: transparent;
        color: white;
        font-family: 'Caveat', cursive;
        font-size: 1.8rem;
        padding: 15px 40px;
        border: 2px solid white;
        border-radius: 30px;
        cursor: pointer;
        transition: all 0.3s ease;
    }

    .next-button:hover {
        background-color: white;
        color: black;
        transform: translateY(-2px);
    }

    .final-message {
        font-family: 'Roboto', sans-serif;
        font-size: 3rem;
        color: white;
        font-weight: 400;
        text-shadow: 2px 2px 8px rgba(255,255,255,0.2);
    }

    @media (max-width: 768px) {
        .main-title {
            font-size: 2.5rem;
        }
        
        .subtitle {
            font-size: 1.2rem;
        }
        
        .button-container {
            flex-direction: column;
            gap: 20px;
        }
        
        .choice-button {
            font-size: 1.5rem;
            padding: 15px 40px;
        }
        
        .message-text {
            font-size: 1.2rem;
        }
        
        .final-message {
            font-size: 2rem;
        }
    }
</style>
