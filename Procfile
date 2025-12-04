#!/bin/bash

# Navegar para a pasta backend
cd backend

# Iniciar a aplicação Flask com Gunicorn
gunicorn --bind=0.0.0.0:8000 --timeout 600 app:app
