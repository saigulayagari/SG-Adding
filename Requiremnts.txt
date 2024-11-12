import streamlit as st

# Title of the app with an emoji
st.markdown("<h1 style='text-align: center; color: purple;'>🌈 Fun Adding App for Toddlers 🌈</h1>", unsafe_allow_html=True)

# Prompt to the user with a colorful header
st.markdown("<h3 style='text-align: center; color: teal;'>Let's add two numbers together!</h3>", unsafe_allow_html=True)

# Get the first number from the user
first_number = st.number_input("🟢 Enter the first number:", min_value=0, step=1)

# Get the second number from the user
second_number = st.number_input("🔵 Enter the second number:", min_value=0, step
