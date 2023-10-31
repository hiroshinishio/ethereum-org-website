---
title: 如何撤销智能合约对你的加密资产的支配权限
description: 指南：如何撤销恶意智能合约的权限
lang: zh
---

# 如何撤销智能合约对您加密资产的支配权限

本指南将引导你，查看所有对你的资金拥有配额权限的智能合约，以及如何撤销它们。

有时，恶意开发者会在智能合约中创建后门，如果不知情的用户与其交互，这些智能合约将能访问你的资金。 常见的情况是，为了在将来节省少量燃料费，这类平台会向用户索要支配**无限量代币**的权限。但这将带来很大的风险。

一旦平台拥有了对你钱包代币的无限访问权，即使你已将资金从平台提现到自己的钱包，它们也可以花掉所有这些代币。 这些怀有恶意的参与者仍能访问你的资金，并将其提现到他们自己的钱包，而你对此毫无办法进行恢复。

唯一的保护措施是：不使用未经测试的新项目，只批准你需要的项目，或定期撤销权限。 所以，你应该怎么做呢？

## 第 1 步：使用撤销权限工具

有几个网站允许你查看与你钱包地址关联的智能合约，并进行撤销。 访问以下网站并连接到你的钱包：

- [Ethallowance](https://ethallowance.com/)（以太坊）
- [Etherscan](https://etherscan.io/tokenapprovalchecker)（以太坊）
- [Cointool](https://cointool.app/approve/eth)（多个网络）
- [Revoke](https://revoke.cash/)（多个网络）
- [Unrekt](https://app.unrekt.net/)（多个网络）
- [EverRevoke](https://everrise.com/everrevoke/)（多个网络）

## 第 2 步：连接到你的钱包

进入网站后，点击“Connect wallet”。 网站会提示你连接到你的钱包。

请确保你的钱包和网站使用相同的网络。 您将只能看到与所选网络相关的智能合约。 例如，如果你连接到以太坊主网，你将只能看到以太坊合约，而看不到其他链上的合约，例如 Polygon。

## 第 3 步：选择你想要撤销的智能合约

你应该可以看到被允许访问你的代币的全部合约，以及支配数额上限。 找到你想要撤销的合约。

如果你不知道选择哪个合约，你可以全部撤销。 这不会给你带来任何麻烦，但下次你想与这些合约互动时，必须重新授予一系列权限。

## 第 4 步：撤销对你资金的权限

一旦你点击撤销，你会在你的钱包中看到一个新的交易建议。 这是预料之中的。 你必须支付手续费，撤销才能成功。 可能需要一分钟到几分钟来处理，视网络而定。

我们建议你几分钟后刷新撤销工具，并重新连接钱包，再次核查撤销的合约是否已从列表中消失。

<mark>我们建议，永远不要让任何项目对你的代币拥有无限的权限，并定期撤销所有代币配额权限。 尤其是在使用上述工具的情况下，撤销代币访问权限绝不应导致资金损失。</mark>

 <br />

<InfoBanner shouldSpaceBetween emoji=":eyes:">
  <div>想了解更多信息？</div>
  <ButtonLink to="/guides/">
    查看我们其他的指南
  </ButtonLink>
</InfoBanner>

## 常见问题

### 撤销代币权限是否也会终止质押、进入质押池、借贷等？

不会，它不会影响你的任何去中心化金融策略。 你的投资仓位和奖励等都不会受到影响。

### 把钱包与项目断开连接，和取消资产支配权限是一个意思吗？

不是，你断开了你的钱包与项目的连接，但如果你已经授予了代币配额权限，它们仍可以使用这些代币。 你需要撤销该权限。

### 合约权限何时到期？

合约权限没有期限限制。 如果你授予合约权限，即使在几年之后，权限依然有效。

### 为什么有些智能合约会设置无限代币配额呢？

项目这样做通常是为了减少所需的请求次数，也就是说用户只需批准一次，并且仅需支付一次交易费。 这虽然方便，但有些网站没有经过时间检验，也没有经过审计，用户不经意地授予权限可能会带来风险。 一些钱包允许你手动限制可以批准的代币额，以降低你的风险。 可询问你的钱包提供者，以获取更多信息。