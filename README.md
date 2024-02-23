# formatoMoneda-Nodejs

const formatearMoneda = (monto) => {
    return new Intl.NumberFormat('en-US', {
        style: 'currency',
        currency: 'USD', // Puedes ajustar la moneda según tus necesidades
    }).format(monto);
};
