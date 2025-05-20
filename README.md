import streamlit as st

st.title("Halo Nadya 👋")
st.write("Ini adalah aplikasi pertama kamu dengan Streamlit!")

uploaded_file = st.file_uploader("Upload file proyek kamu")
if uploaded_file is not None:
    st.success(f"File '{uploaded_file.name}' berhasil diupload.")
