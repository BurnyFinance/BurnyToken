{\rtf1\ansi\ansicpg1252\deff0\nouicompat\deflang1033{\fonttbl{\f0\fnil\fcharset0 Calibri;}}
{\colortbl ;\red0\green0\blue255;}
{\*\generator Riched20 10.0.19041}\viewkind4\uc1 
\pard\sa200\sl276\slmult1\f0\fs22\lang9 // SPDX-License-Identifier: MIT\par
\par
pragma solidity >=0.7.0 <0.8.0;\par
\par
\par
abstract contract Context \{\par
    function _msgSender() internal view virtual returns (address payable) \{\par
        return msg.sender;\par
    \}\par
\par
    function _msgData() internal view virtual returns (bytes memory) \{\par
        this; // silence state mutability warning without generating bytecode - see {{\field{\*\fldinst{HYPERLINK https://github.com/ethereum/solidity/issues/2691 }}{\fldrslt{https://github.com/ethereum/solidity/issues/2691\ul0\cf0}}}}\f0\fs22\par
        return msg.data;\par
    \}\par
\}\par
\par
interface IERC20 \{\par
    /**\par
     * @dev Returns the amount of tokens in existence.\par
     */\par
    function totalSupply() external view returns (uint256);\par
\par
    /**\par
     * @dev Returns the amount of tokens owned by `account`.\par
     */\par
    function balanceOf(address account) external view returns (uint256);\par
\par
    /**\par
     * @dev Moves `amount` tokens from the caller's account to `recipient`.\par
     *\par
     * Returns a boolean value indicating whether the operation succeeded.\par
     *\par
     * Emits a \{Transfer\} event.\par
     */\par
    function transfer(address recipient, uint256 amount) external returns (bool);\par
\par
    /**\par
     * @dev Returns the remaining number of tokens that `spender` will be\par
     * allowed to spend on behalf of `owner` through \{transferFrom\}. This is\par
     * zero by default.\par
     *\par
     * This value changes when \{approve\} or \{transferFrom\} are called.\par
     */\par
    function allowance(address owner, address spender) external view returns (uint256);\par
\par
    /**\par
     * @dev Sets `amount` as the allowance of `spender` over the caller's tokens.\par
     *\par
     * Returns a boolean value indicating whether the operation succeeded.\par
     *\par
     * IMPORTANT: Beware that changing an allowance with this method brings the risk\par
     * that someone may use both the old and the new allowance by unfortunate\par
     * transaction ordering. One possible solution to mitigate this race\par
     * condition is to first reduce the spender's allowance to 0 and set the\par
     * desired value afterwards:\par
     * {{\field{\*\fldinst{HYPERLINK https://github.com/ethereum/EIPs/issues/20#issuecomment-263524729 }}{\fldrslt{https://github.com/ethereum/EIPs/issues/20#issuecomment-263524729\ul0\cf0}}}}\f0\fs22\par
     *\par
     * Emits an \{Approval\} event.\par
     */\par
    function approve(address spender, uint256 amount) external returns (bool);\par
\par
    /**\par
     * @dev Moves `amount` tokens from `sender` to `recipient` using the\par
     * allowance mechanism. `amount` is then deducted from the caller's\par
     * allowance.\par
     *\par
     * Returns a boolean value indicating whether the operation succeeded.\par
     *\par
     * Emits a \{Transfer\} event.\par
     */\par
    function transferFrom(address sender, address recipient, uint256 amount) external returns (bool);\par
\par
    /**\par
     * @dev Emitted when `value` tokens are moved from one account (`from`) to\par
     * another (`to`).\par
     *\par
     * Note that `value` may be zero.\par
     */\par
    event Transfer(address indexed from, address indexed to, uint256 value);\par
\par
    /**\par
     * @dev Emitted when the allowance of a `spender` for an `owner` is set by\par
     * a call to \{approve\}. `value` is the new allowance.\par
     */\par
    event Approval(address indexed owner, address indexed spender, uint256 value);\par
\}\par
\par
\par
library SafeMath \{\par
    /**\par
     * @dev Returns the addition of two unsigned integers, reverting on\par
     * overflow.\par
     *\par
     * Counterpart to Solidity's `+` operator.\par
     *\par
     * Requirements:\par
     *\par
     * - Addition cannot overflow.\par
     */\par
    function add(uint256 a, uint256 b) internal pure returns (uint256) \{\par
        uint256 c = a + b;\par
        require(c >= a, "SafeMath: addition overflow");\par
\par
        return c;\par
    \}\par
\par
    /**\par
     * @dev Returns the subtraction of two unsigned integers, reverting on\par
     * overflow (when the result is negative).\par
     *\par
     * Counterpart to Solidity's `-` operator.\par
     *\par
     * Requirements:\par
     *\par
     * - Subtraction cannot overflow.\par
     */\par
    function sub(uint256 a, uint256 b) internal pure returns (uint256) \{\par
        return sub(a, b, "SafeMath: subtraction overflow");\par
    \}\par
\par
    /**\par
     * @dev Returns the subtraction of two unsigned integers, reverting with custom message on\par
     * overflow (when the result is negative).\par
     *\par
     * Counterpart to Solidity's `-` operator.\par
     *\par
     * Requirements:\par
     *\par
     * - Subtraction cannot overflow.\par
     */\par
    function sub(uint256 a, uint256 b, string memory errorMessage) internal pure returns (uint256) \{\par
        require(b <= a, errorMessage);\par
        uint256 c = a - b;\par
\par
        return c;\par
    \}\par
\par
    /**\par
     * @dev Returns the multiplication of two unsigned integers, reverting on\par
     * overflow.\par
     *\par
     * Counterpart to Solidity's `*` operator.\par
     *\par
     * Requirements:\par
     *\par
     * - Multiplication cannot overflow.\par
     */\par
    function mul(uint256 a, uint256 b) internal pure returns (uint256) \{\par
        // Gas optimization: this is cheaper than requiring 'a' not being zero, but the\par
        // benefit is lost if 'b' is also tested.\par
        // See: {{\field{\*\fldinst{HYPERLINK https://github.com/OpenZeppelin/openzeppelin-contracts/pull/522 }}{\fldrslt{https://github.com/OpenZeppelin/openzeppelin-contracts/pull/522\ul0\cf0}}}}\f0\fs22\par
        if (a == 0) \{\par
            return 0;\par
        \}\par
\par
        uint256 c = a * b;\par
        require(c / a == b, "SafeMath: multiplication overflow");\par
\par
        return c;\par
    \}\par
\par
    /**\par
     * @dev Returns the integer division of two unsigned integers. Reverts on\par
     * division by zero. The result is rounded towards zero.\par
     *\par
     * Counterpart to Solidity's `/` operator. Note: this function uses a\par
     * `revert` opcode (which leaves remaining gas untouched) while Solidity\par
     * uses an invalid opcode to revert (consuming all remaining gas).\par
     *\par
     * Requirements:\par
     *\par
     * - The divisor cannot be zero.\par
     */\par
    function div(uint256 a, uint256 b) internal pure returns (uint256) \{\par
        return div(a, b, "SafeMath: division by zero");\par
    \}\par
\par
    /**\par
     * @dev Returns the integer division of two unsigned integers. Reverts with custom message on\par
     * division by zero. The result is rounded towards zero.\par
     *\par
     * Counterpart to Solidity's `/` operator. Note: this function uses a\par
     * `revert` opcode (which leaves remaining gas untouched) while Solidity\par
     * uses an invalid opcode to revert (consuming all remaining gas).\par
     *\par
     * Requirements:\par
     *\par
     * - The divisor cannot be zero.\par
     */\par
    function div(uint256 a, uint256 b, string memory errorMessage) internal pure returns (uint256) \{\par
        require(b > 0, errorMessage);\par
        uint256 c = a / b;\par
        // assert(a == b * c + a % b); // There is no case in which this doesn't hold\par
\par
        return c;\par
    \}\par
\par
    /**\par
     * @dev Returns the remainder of dividing two unsigned integers. (unsigned integer modulo),\par
     * Reverts when dividing by zero.\par
     *\par
     * Counterpart to Solidity's `%` operator. This function uses a `revert`\par
     * opcode (which leaves remaining gas untouched) while Solidity uses an\par
     * invalid opcode to revert (consuming all remaining gas).\par
     *\par
     * Requirements:\par
     *\par
     * - The divisor cannot be zero.\par
     */\par
    function mod(uint256 a, uint256 b) internal pure returns (uint256) \{\par
        return mod(a, b, "SafeMath: modulo by zero");\par
    \}\par
\par
    /**\par
     * @dev Returns the remainder of dividing two unsigned integers. (unsigned integer modulo),\par
     * Reverts with custom message when dividing by zero.\par
     *\par
     * Counterpart to Solidity's `%` operator. This function uses a `revert`\par
     * opcode (which leaves remaining gas untouched) while Solidity uses an\par
     * invalid opcode to revert (consuming all remaining gas).\par
     *\par
     * Requirements:\par
     *\par
     * - The divisor cannot be zero.\par
     */\par
    function mod(uint256 a, uint256 b, string memory errorMessage) internal pure returns (uint256) \{\par
        require(b != 0, errorMessage);\par
        return a % b;\par
    \}\par
\}\par
\par
\par
contract Ownable is Context \{\par
    address private _owner;\par
\par
    event OwnershipTransferred(address indexed previousOwner, address indexed newOwner);\par
\par
    /**\par
     * @dev Initializes the contract setting the deployer as the initial owner.\par
     */\par
    constructor ()  \{\par
        address msgSender = _msgSender();\par
        _owner = msgSender;\par
        emit OwnershipTransferred(address(0), msgSender);\par
    \}\par
\par
    /**\par
     * @dev Returns the address of the current owner.\par
     */\par
    function owner() public view returns (address) \{\par
        return _owner;\par
    \}\par
\par
    /**\par
     * @dev Throws if called by any account other than the owner.\par
     */\par
    modifier onlyOwner() \{\par
        require(_owner == _msgSender(), "Ownable: caller is not the owner");\par
        _;\par
    \}\par
\par
    /**\par
     * @dev Leaves the contract without owner. It will not be possible to call\par
     * `onlyOwner` functions anymore. Can only be called by the current owner.\par
     *\par
     * NOTE: Renouncing ownership will leave the contract without an owner,\par
     * thereby removing any functionality that is only available to the owner.\par
     */\par
    function renounceOwnership() public virtual onlyOwner \{\par
        emit OwnershipTransferred(_owner, address(0));\par
        _owner = address(0);\par
    \}\par
\par
    /**\par
     * @dev Transfers ownership of the contract to a new account (`newOwner`).\par
     * Can only be called by the current owner.\par
     */\par
    function transferOwnership(address newOwner) public virtual onlyOwner \{\par
        require(newOwner != address(0), "Ownable: new owner is the zero address");\par
        emit OwnershipTransferred(_owner, newOwner);\par
        _owner = newOwner;\par
    \}\par
\}\par
\par
contract BURNY is Context, IERC20, Ownable \{\par
    using SafeMath for uint256;\par
    \par
    mapping (address => uint256) private _balances;\par
\par
    mapping (address => mapping (address => uint256)) private _allowances;\par
\par
\par
    uint256 private _totalSupply = 1000000000000 * 10**18;\par
    \par
    address public charityWallet;\par
\par
    string private _name = 'BURNY.Finance';\par
    string private _symbol = 'BURNY';\par
    uint8 private _decimals = 18;\par
    \par
    uint public burnDisabledAtAmount = 200000000000 * 10**18;\par
    bool public burnEnabled;\par
    \par
    \par
    constructor (address _charityWallet) \{\par
        \par
        _balances[msg.sender] = _totalSupply;\par
        charityWallet = _charityWallet;\par
        burnEnabled = true;\par
        \par
    \}\par
    \par
    function name() public view virtual  returns (string memory) \{\par
        return _name;\par
    \}\par
    \par
    function symbol() public view virtual  returns (string memory) \{\par
        return _symbol;\par
    \}\par
    \par
    function decimals() public view virtual  returns (uint8) \{\par
        return 18;\par
    \}\par
    \par
    function totalSupply() public view virtual override returns (uint256) \{\par
        return _totalSupply;\par
    \}\par
    \par
    function balanceOf(address account) public view virtual override returns (uint256) \{\par
        return _balances[account];\par
    \}\par
    \par
    function transfer(address recipient, uint256 amount) public virtual override returns (bool) \{\par
        _transfer(_msgSender(), recipient, amount);\par
        return true;\par
    \}\par
    \par
    function setBurnEnabled (bool enabled) public onlyOwner() \{\par
        burnEnabled = enabled;\par
    \}\par
    \par
    function allowance(address owner, address spender) public view virtual override returns (uint256) \{\par
        return _allowances[owner][spender];\par
    \}\par
    \par
    function approve(address spender, uint256 amount) public virtual override returns (bool) \{\par
        _approve(_msgSender(), spender, amount);\par
        return true;\par
    \}\par
    \par
    function transferFrom(address sender, address recipient, uint256 amount) public virtual override returns (bool) \{\par
        _transfer(sender, recipient, amount);\par
\par
        uint256 currentAllowance = _allowances[sender][_msgSender()];\par
        require(currentAllowance >= amount, "ERC20: transfer amount exceeds allowance");\par
        _approve(sender, _msgSender(), currentAllowance - amount);\par
\par
        return true;\par
    \}\par
    \par
    function increaseAllowance(address spender, uint256 addedValue) public virtual returns (bool) \{\par
        _approve(_msgSender(), spender, _allowances[_msgSender()][spender] + addedValue);\par
        return true;\par
    \}\par
    \par
    function decreaseAllowance(address spender, uint256 subtractedValue) public virtual returns (bool) \{\par
        uint256 currentAllowance = _allowances[_msgSender()][spender];\par
        require(currentAllowance >= subtractedValue, "ERC20: decreased allowance below zero");\par
        _approve(_msgSender(), spender, currentAllowance - subtractedValue);\par
\par
        return true;\par
    \}\par
    \par
    function _transfer(address sender, address recipient, uint256 amount) internal virtual \{\par
        require(sender != address(0), "ERC20: transfer from the zero address");\par
        require(recipient != address(0), "ERC20: transfer to the zero address");\par
        \par
        uint256 senderBalance = _balances[sender];\par
        require(senderBalance >= amount, "ERC20: transfer amount exceeds balance");\par
        \par
        uint currentTotalSupply = _totalSupply;\par
        if (currentTotalSupply <= burnDisabledAtAmount) \{\par
            burnEnabled = false;\par
        \}\par
        \par
        if (burnEnabled) \{\par
            uint _amount = amount;\par
            uint _charityAmount = amount.div(20);\par
            uint _burnAmount = amount.mul(15).div(100);\par
            uint _transferFee = _charityAmount.add(_burnAmount);\par
            uint _amountToTransfer = _amount.sub(_transferFee);\par
            \par
            _balances[sender] = senderBalance.sub(_amount);\par
            \par
            _totalSupply = _totalSupply.sub(_burnAmount);\par
            \par
            _balances[charityWallet] = _balances[charityWallet].add(_charityAmount);\par
            \par
            _balances[recipient] = _balances[recipient].add(_amountToTransfer);\par
            \par
            emit Transfer(sender, address(0), _burnAmount); \par
\par
            emit Transfer(sender, recipient, amount);\par
        \} \par
        else \{\par
        \par
            _balances[sender] = senderBalance.sub(amount);\par
            _balances[recipient] = _balances[recipient].add(amount);\par
\par
            emit Transfer(sender, recipient, amount);\par
        \}\par
    \}\par
    \par
    \par
    function _approve(address owner, address spender, uint256 amount) internal virtual \{\par
        require(owner != address(0), "ERC20: approve from the zero address");\par
        require(spender != address(0), "ERC20: approve to the zero address");\par
\par
        _allowances[owner][spender] = amount;\par
        emit Approval(owner, spender, amount);\par
    \}\par
    \par
\}\par
\par
}
 