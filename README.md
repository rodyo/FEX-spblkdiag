[![View Sparse block diagonal concatenation on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/46972-sparse-block-diagonal-concatenation)

[![Donate to Rody](https://i.stack.imgur.com/bneea.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4M7RMVNMKAXXQ&source=url)

# FEX-spblkdiag

SPBLKDIAG Block diagonal concatenation of matrix input arguments, with sparse output.

Y = SPBLKDIAG(A,B,...) produces SPARSE(BLKDIAG(A, B, ..)) efficiently, where A, B, ... are matrices of class double (real or complex).

Basically, this is a thin wrapper around MATLAB's own BLKDIAG, since it already supports sparse output. However:

- BLKDIAG does not mention sparse support in its documentation; nor the fact that it is supported, nor how to access the functionality.

- BLKDIAG's name is inconsistent with the function names for any of MATLAB's other sparse functions (SPEYE, SPDIAGS, etc.)

Therefore, until The MathWorks fixes this, this function provides a better documented and more intuitively named alternative to BLKDIAG.

If you can appreaciate this work, please consider [a donation](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4M7RMVNMKAXXQ&source=url).
