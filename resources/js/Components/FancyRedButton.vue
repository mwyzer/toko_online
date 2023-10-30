<template>
    <button class="red-btn">
        <slot/> <!-- slot outlet -->
      </button>
  </template>

  <style>
  .red-btn {
    color: #fff;
    background: linear-gradient(315deg, hsl(337, 94%, 51%) 25%, #647eff);
    border: none;
    padding: 5px 10px;
    margin: 5px;
    border-radius: 8px;
    cursor: pointer;
  }
  </style>
